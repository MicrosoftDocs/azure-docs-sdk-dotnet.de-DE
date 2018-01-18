<Type Name="Transmission" FullName="Microsoft.ApplicationInsights.Channel.Transmission">
  <TypeSignature Language="C#" Value="public class Transmission" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Transmission extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Channel.Transmission" />
  <TypeSignature Language="VB.NET" Value="Public Class Transmission" />
  <TypeSignature Language="F#" Value="type Transmission = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c6a4-101">Implementiert eine asynchrone Übertragung von Daten an einen HTTP POST-Endpunkt an.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-101">Implements an asynchronous transmission of data to an HTTP POST endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal Transmission ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.Transmission.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.Channel.Transmission" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.Channel.Transmission" /> class.</span></span> <span data-ttu-id="9c6a4-103">Diese Überladung wird für Testzwecke.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-103">This overload is for Test purposes.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Transmission (Uri address, System.Collections.Generic.ICollection&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt; telemetryItems, TimeSpan timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class System.Collections.Generic.ICollection`1&lt;class Microsoft.ApplicationInsights.Channel.ITelemetry&gt; telemetryItems, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.Transmission.#ctor(System.Uri,System.Collections.Generic.ICollection{Microsoft.ApplicationInsights.Channel.ITelemetry},System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, telemetryItems As ICollection(Of ITelemetry), Optional timeout As TimeSpan = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.Channel.Transmission : Uri * System.Collections.Generic.ICollection&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt; * TimeSpan -&gt; Microsoft.ApplicationInsights.Channel.Transmission" Usage="new Microsoft.ApplicationInsights.Channel.Transmission (address, telemetryItems, timeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="telemetryItems" Type="System.Collections.Generic.ICollection&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="address">To be added.</param>
        <param name="telemetryItems">To be added.</param>
        <param name="timeout">To be added.</param>
        <summary>
            <span data-ttu-id="9c6a4-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.Channel.Transmission" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-104">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.Channel.Transmission" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Transmission (Uri address, byte[] content, string contentType, string contentEncoding, TimeSpan timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, unsigned int8[] content, string contentType, string contentEncoding, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.Transmission.#ctor(System.Uri,System.Byte[],System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, content As Byte(), contentType As String, contentEncoding As String, Optional timeout As TimeSpan = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.Channel.Transmission : Uri * byte[] * string * string * TimeSpan -&gt; Microsoft.ApplicationInsights.Channel.Transmission" Usage="new Microsoft.ApplicationInsights.Channel.Transmission (address, content, contentType, contentEncoding, timeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="content" Type="System.Byte[]" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="contentEncoding" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="address">To be added.</param>
        <param name="content">To be added.</param>
        <param name="contentType">To be added.</param>
        <param name="contentEncoding">To be added.</param>
        <param name="timeout">To be added.</param>
        <summary>
            <span data-ttu-id="9c6a4-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.Channel.Transmission" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-105">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.Channel.Transmission" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public byte[] Content { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.Transmission.Content" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Content As Byte()" />
      <MemberSignature Language="F#" Value="member this.Content : byte[]" Usage="Microsoft.ApplicationInsights.Channel.Transmission.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-106">Ruft den Inhalt der Übertragung ab.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-106">Gets the content of the transmission.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.Transmission.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string" Usage="Microsoft.ApplicationInsights.Channel.Transmission.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-107">Ruft die Codierung Methode der Übertragung ab.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-107">Gets the encoding method of the transmission.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.Transmission.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string" Usage="Microsoft.ApplicationInsights.Channel.Transmission.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-108">Ruft den Inhaltstyp der Übertragung ab.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-108">Gets the content's type of the transmission.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRequest">
      <MemberSignature Language="C#" Value="protected virtual System.Net.WebRequest CreateRequest (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Net.WebRequest CreateRequest(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.Transmission.CreateRequest(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateRequest (address As Uri) As WebRequest" />
      <MemberSignature Language="F#" Value="abstract member CreateRequest : Uri -&gt; System.Net.WebRequest&#xA;override this.CreateRequest : Uri -&gt; System.Net.WebRequest" Usage="transmission.CreateRequest address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.WebRequest</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="9c6a4-109">Die Adresse in der webanforderung.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-109">The Address in the web request.</span></span></param>
        <summary>
            <span data-ttu-id="9c6a4-110">Erstellt eine Web-Post-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-110">Creates a post web request.</span></span>  
            </summary>
        <returns><span data-ttu-id="9c6a4-111">Eine webanforderung, die auf die <c>Adresse</c>.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-111">A web request pointing to the <c>Address</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointAddress">
      <MemberSignature Language="C#" Value="public Uri EndpointAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri EndpointAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.Transmission.EndpointAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndpointAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.EndpointAddress : Uri" Usage="Microsoft.ApplicationInsights.Channel.Transmission.EndpointAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-112">Ruft die Adresse des Endpunkts an die Übertragungswarteschlange gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-112">Gets the Address of the endpoint to which transmission will be sent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.Transmission.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.ApplicationInsights.Channel.Transmission.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-113">Ruft eine Id der Übertragung ab.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-113">Gets an id of the transmission.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.ApplicationInsights.Extensibility.Implementation.HttpWebResponseWrapper&gt; SendAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ApplicationInsights.Extensibility.Implementation.HttpWebResponseWrapper&gt; SendAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.Transmission.SendAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SendAsync () As Task(Of HttpWebResponseWrapper)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ApplicationInsights.Extensibility.Implementation.HttpWebResponseWrapper&gt;&#xA;override this.SendAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ApplicationInsights.Extensibility.Implementation.HttpWebResponseWrapper&gt;" Usage="transmission.SendAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ApplicationInsights.Channel.Transmission/&lt;SendAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ApplicationInsights.Extensibility.Implementation.HttpWebResponseWrapper&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-114">Führt die Anforderung, die die aktuelle Übertragung darstellt.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-114">Executes the request that the current transmission represents.</span></span>
            </summary>
        <returns><span data-ttu-id="9c6a4-115">Die Aufgabe, der "await".</span><span class="sxs-lookup"><span data-stu-id="9c6a4-115">The task to await.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Split">
      <MemberSignature Language="C#" Value="public virtual Tuple&lt;Microsoft.ApplicationInsights.Channel.Transmission,Microsoft.ApplicationInsights.Channel.Transmission&gt; Split (Func&lt;int,int&gt; calculateLength);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Tuple`2&lt;class Microsoft.ApplicationInsights.Channel.Transmission, class Microsoft.ApplicationInsights.Channel.Transmission&gt; Split(class System.Func`2&lt;int32, int32&gt; calculateLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Channel.Transmission.Split(System.Func{System.Int32,System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Split (calculateLength As Func(Of Integer, Integer)) As Tuple(Of Transmission, Transmission)" />
      <MemberSignature Language="F#" Value="abstract member Split : Func&lt;int, int&gt; -&gt; Microsoft.ApplicationInsights.Channel.Transmission * Microsoft.ApplicationInsights.Channel.Transmission&#xA;override this.Split : Func&lt;int, int&gt; -&gt; Microsoft.ApplicationInsights.Channel.Transmission * Microsoft.ApplicationInsights.Channel.Transmission" Usage="transmission.Split calculateLength" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Tuple&lt;Microsoft.ApplicationInsights.Channel.Transmission,Microsoft.ApplicationInsights.Channel.Transmission&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="calculateLength" Type="System.Func&lt;System.Int32,System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="calculateLength">To be added.</param>
        <summary>
            <span data-ttu-id="9c6a4-116">Teilt das Übertragungsobjekt in zwei Teile, die mit einer Methode, um die Länge des ersten Teils basierend auf der Länge der Übertragung zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-116">Splits the Transmission object into two pieces using a method to determine the length of the first piece based off of the length of the transmission.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9c6a4-117">Ein Tupel mit dem ersten Element wird ein Übertragungsobjekt mit n ITelemetry-Objekten und das zweite Element wird ein Übertragungsobjekt mit den verbleibenden ITelemetry-Objekten.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-117">A tuple with the first item being a Transmission object with n ITelemetry objects and the second item being a Transmission object with the remaining ITelemetry objects.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetryItems">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ICollection&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt; TelemetryItems { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ICollection`1&lt;class Microsoft.ApplicationInsights.Channel.ITelemetry&gt; TelemetryItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.Transmission.TelemetryItems" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetryItems As ICollection(Of ITelemetry)" />
      <MemberSignature Language="F#" Value="member this.TelemetryItems : System.Collections.Generic.ICollection&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt;" Usage="Microsoft.ApplicationInsights.Channel.Transmission.TelemetryItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.ApplicationInsights.Channel.ITelemetry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-118">Ruft die Anzahl der Telemetrie-Elemente in die Übertragung an.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-118">Gets the number of telemetry items in the transmission.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public TimeSpan Timeout { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Channel.Transmission.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Timeout : TimeSpan" Usage="Microsoft.ApplicationInsights.Channel.Transmission.Timeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c6a4-119">Ruft einen Timeoutwert für die Übertragung an.</span><span class="sxs-lookup"><span data-stu-id="9c6a4-119">Gets a timeout value for the transmission.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>