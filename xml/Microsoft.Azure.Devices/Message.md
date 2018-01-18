<Type Name="Message" FullName="Microsoft.Azure.Devices.Message">
  <TypeSignature Language="C#" Value="public sealed class Message : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Message extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Message" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Message&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type Message = class&#xA;    interface IDisposable&#xA;    interface IReadOnlyIndicator" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="4e483-101">Die Datenstruktur darstellen, die Nachricht, die für die Interaktion mit IotHub verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="4e483-101">The data structure represent the message that is used for interacting with IotHub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e483-102">Standardkonstruktor ohne Text-Daten</span><span class="sxs-lookup"><span data-stu-id="4e483-102">Default constructor with no body data</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (byte[] byteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] byteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (byteArray As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Message : byte[] -&gt; Microsoft.Azure.Devices.Message" Usage="new Microsoft.Azure.Devices.Message byteArray" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="byteArray" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="byteArray"><span data-ttu-id="4e483-103">ein Bytearray der verwendet wird, um den Antworttext-Datenstrom zu bilden.</span><span class="sxs-lookup"><span data-stu-id="4e483-103">a byte array which will be used to form the body stream</span></span></param>
        <summary>
            <span data-ttu-id="4e483-104">Konstruktor befindlichen Eingabebytearrays als Text</span><span class="sxs-lookup"><span data-stu-id="4e483-104">Constructor which uses the input byte array as the body</span></span>
            </summary>
        <remarks><span data-ttu-id="4e483-105">Benutzer sollten Eingabebytearrays als unveränderlich behandeln, beim Senden der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4e483-105">user should treat the input byte array as immutable when sending the message.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Message (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Message : System.IO.Stream -&gt; Microsoft.Azure.Devices.Message" Usage="new Microsoft.Azure.Devices.Message stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="4e483-106">Ein Datenstrom, der als Antworttext-Datenstrom verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4e483-106">a stream which will be used as body stream.</span></span></param>
        <summary>
            <span data-ttu-id="4e483-107">Der Konstruktor der Argument-Stream als Antworttext-Datenstrom verwendet.</span><span class="sxs-lookup"><span data-stu-id="4e483-107">Constructor which uses the argument stream as the body stream.</span></span>
            </summary>
        <remarks><span data-ttu-id="4e483-108">Benutzer muss Besitzer der Freigabe des Datenstroms für die Verwendung dieses Konstruktors.</span><span class="sxs-lookup"><span data-stu-id="4e483-108">User is expected to own the disposing of the stream when using this constructor.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Ack">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.DeliveryAcknowledgement Ack { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Devices.DeliveryAcknowledgement Ack" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.Ack" />
      <MemberSignature Language="VB.NET" Value="Public Property Ack As DeliveryAcknowledgement" />
      <MemberSignature Language="F#" Value="member this.Ack : Microsoft.Azure.Devices.DeliveryAcknowledgement with get, set" Usage="Microsoft.Azure.Devices.Message.Ack" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.DeliveryAcknowledgement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-109">Gibt an, ob Verbrauch oder den Ablauf der Nachricht an die feedbackwarteschlange Übermitteln von Daten sollten</span><span class="sxs-lookup"><span data-stu-id="4e483-109">Indicates whether consumption or expiration of the message should post data to the feedback queue</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Message Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Devices.Message Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Message" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.Azure.Devices.Message" Usage="message.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Message</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e483-110">Stellt einen Klon des aktuellen Ereignisdateninstanz an.</span><span class="sxs-lookup"><span data-stu-id="4e483-110">Makes a clone of the current event data instance.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="4e483-111">löst aus, wenn die Ereignisdaten bereits verworfen wurde.</span><span class="sxs-lookup"><span data-stu-id="4e483-111">throws if the event data has already been disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.Azure.Devices.Message.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-112">Verwendet, um den Inhalt der Nachricht Codierungstyp anzugeben.</span><span class="sxs-lookup"><span data-stu-id="4e483-112">Used to specify the content encoding type of the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Devices.Message.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-113">Dient zum Angeben des Inhaltstyp der Nachricht.</span><span class="sxs-lookup"><span data-stu-id="4e483-113">Used to specify the content type of the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.Devices.Message.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-114">Bei der Nachricht antworten und Feedback verwendet</span><span class="sxs-lookup"><span data-stu-id="4e483-114">Used in message responses and feedback</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime CreationTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreationTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.CreationTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreationTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.Devices.Message.CreationTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-115">Benutzerdefinierte Date-Eigenschaft, die vom Absender der Nachricht festgelegt.</span><span class="sxs-lookup"><span data-stu-id="4e483-115">Custom date property set by the originator of the message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="message.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e483-116">Verwerfen der aktuellen Ereignisinstanz Daten</span><span class="sxs-lookup"><span data-stu-id="4e483-116">Dispose the current event data instance</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiryTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiryTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.ExpiryTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiryTimeUtc : DateTime with get, set" Usage="Microsoft.Azure.Devices.Message.ExpiryTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-117">[Optional] Die Zeit, wenn diese Meldung berücksichtigt ist, abgelaufen</span><span class="sxs-lookup"><span data-stu-id="4e483-117">[Optional] The time when this message is considered expired</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBodyStream">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetBodyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetBodyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.GetBodyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBodyStream () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetBodyStream : unit -&gt; System.IO.Stream" Usage="message.GetBodyStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e483-118">Der Antworttext-Datenstrom von der aktuellen Ereignisinstanz Daten zurückgeben</span><span class="sxs-lookup"><span data-stu-id="4e483-118">Return the body stream of the current event data instance</span></span>
            </summary>
        <returns />
        <remarks><span data-ttu-id="4e483-119">Diese Methode kann nur einmal aufgerufen werden, und anschließend Methode löst <see cref="T:System.InvalidOperationException" />.</span><span class="sxs-lookup"><span data-stu-id="4e483-119">This method can only be called once and afterwards method will throw <see cref="T:System.InvalidOperationException" />.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4e483-120">löst aus, wenn die Methode aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="4e483-120">throws if the method has been called.</span></span></exception>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="4e483-121">löst aus, wenn die Ereignisdaten bereits verworfen wurde.</span><span class="sxs-lookup"><span data-stu-id="4e483-121">throws if the event data has already been disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetBytes">
      <MemberSignature Language="C#" Value="public byte[] GetBytes ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetBytes() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Message.GetBytes" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBytes () As Byte()" />
      <MemberSignature Language="F#" Value="member this.GetBytes : unit -&gt; byte[]" Usage="message.GetBytes " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e483-122">Diese Methoden zurück den Antworttext-Datenstrom als Bytearray</span><span class="sxs-lookup"><span data-stu-id="4e483-122">This methods return the body stream as a byte array</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4e483-123">löst aus, wenn die Methode aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="4e483-123">throws if the method has been called.</span></span></exception>
        <exception cref="T:System.ObjectDisposedException"><span data-ttu-id="4e483-124">löst aus, wenn die Ereignisdaten bereits verworfen wurde.</span><span class="sxs-lookup"><span data-stu-id="4e483-124">throws if the event data has already been disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public string LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As String" />
      <MemberSignature Language="F#" Value="member this.LockToken : string" Usage="Microsoft.Azure.Devices.Message.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-125">[Erforderlich] LockToken der empfangenen Nachricht</span><span class="sxs-lookup"><span data-stu-id="4e483-125">[Required] LockToken of the received message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.Azure.Devices.Message.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-126">[Erforderlich für zwei Weise, wie Anforderungen] Verwendet, um bidirektionale Kommunikation zu korrelieren.</span><span class="sxs-lookup"><span data-stu-id="4e483-126">[Required for two way requests] Used to correlate two-way communication.</span></span> <span data-ttu-id="4e483-127">: Ein Groß-/Kleinschreibung Formatzeichenfolge (bis zu 128 Zeichen lang) der alphanumerische ASCII-7-Bit-Zeichen</span><span class="sxs-lookup"><span data-stu-id="4e483-127">Format: A case-sensitive string ( up to 128 char long) of ASCII 7-bit alphanumeric chars</span></span> 
            + <span data-ttu-id="4e483-128">{'-', ':', '/', '\', '.', '+', '%', '_', '#', '\*', '?', '!', '(', ')', ',', '=', '@', ';', '$', '''}.</span><span class="sxs-lookup"><span data-stu-id="4e483-128">{'-', ':', '/', '\', '.', '+', '%', '_', '#', '\*', '?', '!', '(', ')', ',', '=', '@', ';', '$', '''}.</span></span> <span data-ttu-id="4e483-129">Nicht alphanumerische Zeichen sind in RFC URN.</span><span class="sxs-lookup"><span data-stu-id="4e483-129">Non-alphanumeric characters are from URN RFC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageSchema">
      <MemberSignature Language="C#" Value="public string MessageSchema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageSchema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.MessageSchema" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageSchema As String" />
      <MemberSignature Language="F#" Value="member this.MessageSchema : string with get, set" Usage="Microsoft.Azure.Devices.Message.MessageSchema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-130">Wird verwendet, um das Schema des Nachrichteninhalts anzugeben.</span><span class="sxs-lookup"><span data-stu-id="4e483-130">Used to specify the schema of the message content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Devices.Message.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-131">Ruft das Wörterbuch von Eigenschaften der Benutzerrolle die wann festgelegt werden Benutzer die Daten senden.</span><span class="sxs-lookup"><span data-stu-id="4e483-131">Gets the dictionary of user properties which are set when user send the data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.Azure.Devices.Message.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-132">[Erforderlich] Ziel der Nachricht</span><span class="sxs-lookup"><span data-stu-id="4e483-132">[Required] Destination of the message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Message.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.Azure.Devices.Message.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e483-133">[In Feedback Nachrichten erforderlich] Dient zum Angeben des Ursprungs von Nachrichten vom Hub Gerät generiert.</span><span class="sxs-lookup"><span data-stu-id="4e483-133">[Required in feedback messages] Used to specify the origin of messages generated by device hub.</span></span> <span data-ttu-id="4e483-134">Wert: "{Hub-Name} /"</span><span class="sxs-lookup"><span data-stu-id="4e483-134">Possible value: “{hub name}/”</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>