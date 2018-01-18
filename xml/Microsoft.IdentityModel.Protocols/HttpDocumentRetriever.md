<Type Name="HttpDocumentRetriever" FullName="Microsoft.IdentityModel.Protocols.HttpDocumentRetriever">
  <TypeSignature Language="C#" Value="public class HttpDocumentRetriever : Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpDocumentRetriever extends System.Object implements class Microsoft.IdentityModel.Protocols.IDocumentRetriever" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpDocumentRetriever&#xA;Implements IDocumentRetriever" />
  <TypeSignature Language="F#" Value="type HttpDocumentRetriever = class&#xA;    interface IDocumentRetriever" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Protocols.IDocumentRetriever</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a3857-101">Ruft Metadateninformationen, die mithilfe von HttpClient ab.</span><span class="sxs-lookup"><span data-stu-id="a3857-101">Retrieves metadata information using HttpClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpDocumentRetriever ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a3857-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3857-102">Initializes a new instance of the <see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpDocumentRetriever (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Protocols.HttpDocumentRetriever : System.Net.Http.HttpClient -&gt; Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" Usage="new Microsoft.IdentityModel.Protocols.HttpDocumentRetriever httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
          <see cref="T:System.Net.Http.HttpClient" />
        </param>
        <summary>
            <span data-ttu-id="a3857-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" /> Klasse mit einer angegebenen "HttpClient".</span><span class="sxs-lookup"><span data-stu-id="a3857-103">Initializes a new instance of the <see cref="T:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever" /> class with a specified httpClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="a3857-104">"HttpClient" ist null.</span><span class="sxs-lookup"><span data-stu-id="a3857-104">'httpClient' is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetDocumentAsync (string address, System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; GetDocumentAsync(string address, valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.GetDocumentAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDocumentAsync (address As String, cancel As CancellationToken) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.GetDocumentAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="httpDocumentRetriever.GetDocumentAsync (address, cancel)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IDocumentRetriever.GetDocumentAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.DebuggerStepThrough</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Protocols.HttpDocumentRetriever/&lt;GetDocumentAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="a3857-105">Speicherort des Dokuments</span><span class="sxs-lookup"><span data-stu-id="a3857-105">Location of document</span></span></param>
        <param name="cancel"><span data-ttu-id="a3857-106">Ein Abbruchtoken, das von anderen Objekten oder Threads verwendet werden kann, um Nachricht vom Abbruch zu empfangen.</span><span class="sxs-lookup"><span data-stu-id="a3857-106">A cancellation token that can be used by other objects or threads to receive notice of cancellation.</span></span> <see cref="T:System.Threading.CancellationToken" /></param>
        <summary>
            <span data-ttu-id="a3857-107">Gibt eine Aufgabe, die eine Zeichenfolge, die eine Konvertierung von remote Dokument Abschluss unter Verwendung der angegebenen Adresse enthält.</span><span class="sxs-lookup"><span data-stu-id="a3857-107">Returns a task which contains a string converted from remote document when completed, by using the provided address.</span></span>
            </summary>
        <returns><span data-ttu-id="a3857-108">Dokumentieren Sie als Zeichenfolge</span><span class="sxs-lookup"><span data-stu-id="a3857-108">Document as a string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireHttps">
      <MemberSignature Language="C#" Value="public bool RequireHttps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequireHttps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.RequireHttps" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireHttps As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequireHttps : bool with get, set" Usage="Microsoft.IdentityModel.Protocols.HttpDocumentRetriever.RequireHttps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3857-109">Erfordert sicheren Https-Kanal zum Senden von Anforderungen...</span><span class="sxs-lookup"><span data-stu-id="a3857-109">Requires Https secure channel for sending requests..</span></span> <span data-ttu-id="a3857-110">Dies ist aus Sicherheitsgründen standardmäßig eingeschaltet.</span><span class="sxs-lookup"><span data-stu-id="a3857-110">This is turned ON by default for security reasons.</span></span> <span data-ttu-id="a3857-111">Es wird empfohlen, nicht vom HTTP-Adressen abrufen dürfen standardmäßig.</span><span class="sxs-lookup"><span data-stu-id="a3857-111">It is RECOMMENDED that you do not allow retrieval from http addresses by default.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>