<Type Name="HttpRequestInfo" FullName="Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo">
  <TypeSignature Language="C#" Value="public class HttpRequestInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpRequestInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpRequestInfo" />
  <TypeSignature Language="F#" Value="type HttpRequestInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="49045-101">Die Informationen für den Http-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="49045-101">The Http request info.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRequestInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49045-102">Initialisiert eine neue Instanz der HttpRequestInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="49045-102">Initializes a new instance of the HttpRequestInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRequestInfo (string clientRequestId = null, string clientIpAddress = null, string method = null, string uri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientRequestId, string clientIpAddress, string method, string uri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As String = null, Optional clientIpAddress As String = null, Optional method As String = null, Optional uri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo : string * string * string * string -&gt; Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo" Usage="new Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo (clientRequestId, clientIpAddress, method, uri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRequestId" Type="System.String" />
        <Parameter Name="clientIpAddress" Type="System.String" />
        <Parameter Name="method" Type="System.String" />
        <Parameter Name="uri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientRequestId"><span data-ttu-id="49045-103">die Clientanforderungs-Id.</span><span class="sxs-lookup"><span data-stu-id="49045-103">the client request id.</span></span></param>
        <param name="clientIpAddress"><span data-ttu-id="49045-104">der Client-IP-Adresse</span><span class="sxs-lookup"><span data-stu-id="49045-104">the client Ip Address</span></span></param>
        <param name="method"><span data-ttu-id="49045-105">die HTTP-Anforderungsmethode.</span><span class="sxs-lookup"><span data-stu-id="49045-105">the Http request method.</span></span></param>
        <param name="uri"><span data-ttu-id="49045-106">Der Uri.</span><span class="sxs-lookup"><span data-stu-id="49045-106">the Uri.</span></span></param>
        <summary>
            <span data-ttu-id="49045-107">Initialisiert eine neue Instanz der HttpRequestInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="49045-107">Initializes a new instance of the HttpRequestInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientIpAddress">
      <MemberSignature Language="C#" Value="public string ClientIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.ClientIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.ClientIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.ClientIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49045-108">Ruft ab oder legt die Client-IP-Adresse</span><span class="sxs-lookup"><span data-stu-id="49045-108">Gets or sets the client Ip Address</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public string ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.ClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientRequestId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49045-109">Ruft ab oder legt die Client-Anforderungs-Id.</span><span class="sxs-lookup"><span data-stu-id="49045-109">Gets or sets the client request id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Method">
      <MemberSignature Language="C#" Value="public string Method { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Method" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.Method" />
      <MemberSignature Language="VB.NET" Value="Public Property Method As String" />
      <MemberSignature Language="F#" Value="member this.Method : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.Method" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="method")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49045-110">Ruft ab oder legt die HTTP-Anforderungsmethode.</span><span class="sxs-lookup"><span data-stu-id="49045-110">Gets or sets the Http request method.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public string Uri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.Uri" />
      <MemberSignature Language="VB.NET" Value="Public Property Uri As String" />
      <MemberSignature Language="F#" Value="member this.Uri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49045-111">Ruft ab oder legt den Uri fest.</span><span class="sxs-lookup"><span data-stu-id="49045-111">Gets or sets the Uri.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>