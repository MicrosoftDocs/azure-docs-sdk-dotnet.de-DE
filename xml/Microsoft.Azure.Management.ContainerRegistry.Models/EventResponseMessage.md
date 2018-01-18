<Type Name="EventResponseMessage" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage">
  <TypeSignature Language="C#" Value="public class EventResponseMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventResponseMessage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class EventResponseMessage" />
  <TypeSignature Language="F#" Value="type EventResponseMessage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="810b1-101">Die Ereignis-Antwortnachricht empfangen aus dem Dienst-URI.</span><span class="sxs-lookup"><span data-stu-id="810b1-101">The event response message received from the service URI.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventResponseMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="810b1-102">Initialisiert eine neue Instanz der EventResponseMessage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="810b1-102">Initializes a new instance of the EventResponseMessage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventResponseMessage (string content = null, System.Collections.Generic.IDictionary&lt;string,string&gt; headers = null, string reasonPhrase = null, string statusCode = null, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string content, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; headers, string reasonPhrase, string statusCode, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional content As String = null, Optional headers As IDictionary(Of String, String) = null, Optional reasonPhrase As String = null, Optional statusCode As String = null, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage : string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage (content, headers, reasonPhrase, statusCode, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="content" Type="System.String" />
        <Parameter Name="headers" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="reasonPhrase" Type="System.String" />
        <Parameter Name="statusCode" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="content"><span data-ttu-id="810b1-103">Der Inhalt der Antwortnachricht Ereignis.</span><span class="sxs-lookup"><span data-stu-id="810b1-103">The content of the event response message.</span></span></param>
        <param name="headers"><span data-ttu-id="810b1-104">Die Header der Antwortnachricht Ereignis.</span><span class="sxs-lookup"><span data-stu-id="810b1-104">The headers of the event response message.</span></span></param>
        <param name="reasonPhrase"><span data-ttu-id="810b1-105">Der ursachenbegriff der Antwortnachricht Ereignis.</span><span class="sxs-lookup"><span data-stu-id="810b1-105">The reason phrase of the event response message.</span></span></param>
        <param name="statusCode"><span data-ttu-id="810b1-106">Der Statuscode der Antwortnachricht Ereignis.</span><span class="sxs-lookup"><span data-stu-id="810b1-106">The status code of the event response message.</span></span></param>
        <param name="version"><span data-ttu-id="810b1-107">Die HTTP-Nachrichtenversion.</span><span class="sxs-lookup"><span data-stu-id="810b1-107">The HTTP message version.</span></span></param>
        <summary>
            <span data-ttu-id="810b1-108">Initialisiert eine neue Instanz der EventResponseMessage-Klasse.</span><span class="sxs-lookup"><span data-stu-id="810b1-108">Initializes a new instance of the EventResponseMessage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public string Content { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Content" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.Content" />
      <MemberSignature Language="VB.NET" Value="Public Property Content As String" />
      <MemberSignature Language="F#" Value="member this.Content : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.Content" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="content")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="810b1-109">Ruft ab oder legt den Inhalt der Antwortnachricht Ereignis fest.</span><span class="sxs-lookup"><span data-stu-id="810b1-109">Gets or sets the content of the event response message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="810b1-110">Ruft ab oder legt die Header der Antwortnachricht Ereignis.</span><span class="sxs-lookup"><span data-stu-id="810b1-110">Gets or sets the headers of the event response message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReasonPhrase">
      <MemberSignature Language="C#" Value="public string ReasonPhrase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReasonPhrase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.ReasonPhrase" />
      <MemberSignature Language="VB.NET" Value="Public Property ReasonPhrase As String" />
      <MemberSignature Language="F#" Value="member this.ReasonPhrase : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.ReasonPhrase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reasonPhrase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="810b1-111">Ruft ab oder legt den ursachenbegriff der Antwortnachricht Ereignis.</span><span class="sxs-lookup"><span data-stu-id="810b1-111">Gets or sets the reason phrase of the event response message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public string StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As String" />
      <MemberSignature Language="F#" Value="member this.StatusCode : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="810b1-112">Ruft ab oder legt den Statuscode der Antwortnachricht Ereignis.</span><span class="sxs-lookup"><span data-stu-id="810b1-112">Gets or sets the status code of the event response message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.EventResponseMessage.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="810b1-113">Ruft die HTTP-Nachrichtenversion ab oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="810b1-113">Gets or sets the HTTP message version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>