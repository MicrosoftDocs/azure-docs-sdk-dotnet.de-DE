<Type Name="ZoneDeleteResultInner" FullName="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner">
  <TypeSignature Language="C#" Value="public class ZoneDeleteResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ZoneDeleteResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ZoneDeleteResultInner" />
  <TypeSignature Language="F#" Value="type ZoneDeleteResultInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="27f7d-101">Die Antwort auf einen Vorgang zum Löschen der Zone.</span><span class="sxs-lookup"><span data-stu-id="27f7d-101">The response to a Zone Delete operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ZoneDeleteResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="27f7d-102">Initialisiert eine neue Instanz der ZoneDeleteResultInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="27f7d-102">Initializes a new instance of the ZoneDeleteResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ZoneDeleteResultInner (string azureAsyncOperation = null, Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus&gt; status = null, Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode&gt; statusCode = null, string requestId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string azureAsyncOperation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus&gt; status, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode&gt; statusCode, string requestId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus},System.Nullable{Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional azureAsyncOperation As String = null, Optional status As Nullable(Of OperationStatus) = null, Optional statusCode As Nullable(Of HttpStatusCode) = null, Optional requestId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner : string * Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus&gt; * Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode&gt; * string -&gt; Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner" Usage="new Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner (azureAsyncOperation, status, statusCode, requestId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="azureAsyncOperation" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus&gt;" />
        <Parameter Name="statusCode" Type="System.Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode&gt;" />
        <Parameter Name="requestId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="azureAsyncOperation"><span data-ttu-id="27f7d-103">Benutzer können einen GET-Befehl auf Azure-AsyncOperation zum Abrufen des Status ihrer Delete Zone Vorgänge ausführen.</span><span class="sxs-lookup"><span data-stu-id="27f7d-103">Users can perform a Get on Azure-AsyncOperation to get the status of their delete Zone operations.</span></span></param>
        <param name="status"><span data-ttu-id="27f7d-104">Folgende Werte sind möglich: "InProgress", "Erfolgreich abgeschlossen", "Fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="27f7d-104">Possible values include: 'InProgress', 'Succeeded', 'Failed'</span></span></param>
        <param name="statusCode"><span data-ttu-id="27f7d-105">Folgende Werte sind möglich: "Continue", "SwitchingProtocols", "OK", "Created", "Akzeptiert", "NonAuthoritativeInformation", "NoContent", "ResetContent", "PartialContent", "MultipleChoices',"Mehrdeutig","MovedPermanently","Verschoben","Gefunden,"" Umleiten ","SeeOther","RedirectMethod","NotModified","UseProxy","Nicht verwendet","TemporaryRedirect","RedirectKeepVerb","BadRequest","nicht autorisiert","PaymentRequired","Unzulässig","NotFound","MethodNotAllowed","Antwortformat"," ProxyAuthenticationRequired', 'RequestTimeout', "In Konflikt stehen", "Weg", "Length", "Dass die Streamingendpunkteigenschaft", "RequestEntityTooLarge", "RequestUriTooLong", "UnsupportedMediaType", "RequestedRangeNotSatisfiable", "ExpectationFailed", " UpgradeRequired ","InternalServerError","NotImplemented","BadGateway","ServiceUnavailable","GatewayTimeout","HttpVersionNotSupported"</span><span class="sxs-lookup"><span data-stu-id="27f7d-105">Possible values include: 'Continue', 'SwitchingProtocols', 'OK', 'Created', 'Accepted', 'NonAuthoritativeInformation', 'NoContent', 'ResetContent', 'PartialContent', 'MultipleChoices', 'Ambiguous', 'MovedPermanently', 'Moved', 'Found', 'Redirect', 'SeeOther', 'RedirectMethod', 'NotModified', 'UseProxy', 'Unused', 'TemporaryRedirect', 'RedirectKeepVerb', 'BadRequest', 'Unauthorized', 'PaymentRequired', 'Forbidden', 'NotFound', 'MethodNotAllowed', 'NotAcceptable', 'ProxyAuthenticationRequired', 'RequestTimeout', 'Conflict', 'Gone', 'LengthRequired', 'PreconditionFailed', 'RequestEntityTooLarge', 'RequestUriTooLong', 'UnsupportedMediaType', 'RequestedRangeNotSatisfiable', 'ExpectationFailed', 'UpgradeRequired', 'InternalServerError', 'NotImplemented', 'BadGateway', 'ServiceUnavailable', 'GatewayTimeout', 'HttpVersionNotSupported'</span></span></param>
        <param name="requestId">To be added.</param>
        <summary>
            <span data-ttu-id="27f7d-106">Initialisiert eine neue Instanz der ZoneDeleteResultInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="27f7d-106">Initializes a new instance of the ZoneDeleteResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureAsyncOperation">
      <MemberSignature Language="C#" Value="public string AzureAsyncOperation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureAsyncOperation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.AzureAsyncOperation" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureAsyncOperation As String" />
      <MemberSignature Language="F#" Value="member this.AzureAsyncOperation : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.AzureAsyncOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureAsyncOperation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27f7d-107">Ruft ab oder legt ihn fest Benutzer können, führen Sie einen Get für Azure-AsyncOperation, um den Status des ihrer Löschung Zone Vorgänge abzurufen.</span><span class="sxs-lookup"><span data-stu-id="27f7d-107">Gets or sets users can perform a Get on Azure-AsyncOperation to get the status of their delete Zone operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requestId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of OperationStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27f7d-108">Ruft ab oder legt folgende Werte möglich sind: "InProgress", "Erfolgreich abgeschlossen", "Fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="27f7d-108">Gets or sets possible values include: 'InProgress', 'Succeeded', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode&gt; StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode&gt; StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As Nullable(Of HttpStatusCode)" />
      <MemberSignature Language="F#" Value="member this.StatusCode : Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode&gt; with get, set" Usage="Microsoft.Azure.Management.Dns.Fluent.Models.ZoneDeleteResultInner.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Dns.Fluent.Models.HttpStatusCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27f7d-109">Ruft ab oder legt folgende Werte möglich sind: "Continue", "SwitchingProtocols", "OK", "Erstellt", "Akzeptiert", "NonAuthoritativeInformation", "NoContent", "ResetContent", "PartialContent", "MultipleChoices',"Mehrdeutig","MovedPermanently","Verschobener"," Gefunden ","Umleiten","SeeOther","RedirectMethod","NotModified","UseProxy","Nicht verwendet","TemporaryRedirect","RedirectKeepVerb","BadRequest","Nicht autorisiert","PaymentRequired","Unzulässig","NotFound","MethodNotAllowed","Antwortformat"," ProxyAuthenticationRequired', 'RequestTimeout', "In Konflikt stehen", "Weg", "Length", "Dass die Streamingendpunkteigenschaft", "RequestEntityTooLarge", "RequestUriTooLong", "UnsupportedMediaType", "RequestedRangeNotSatisfiable", "ExpectationFailed", " UpgradeRequired ","InternalServerError","NotImplemented","BadGateway","ServiceUnavailable","GatewayTimeout","HttpVersionNotSupported"</span><span class="sxs-lookup"><span data-stu-id="27f7d-109">Gets or sets possible values include: 'Continue', 'SwitchingProtocols', 'OK', 'Created', 'Accepted', 'NonAuthoritativeInformation', 'NoContent', 'ResetContent', 'PartialContent', 'MultipleChoices', 'Ambiguous', 'MovedPermanently', 'Moved', 'Found', 'Redirect', 'SeeOther', 'RedirectMethod', 'NotModified', 'UseProxy', 'Unused', 'TemporaryRedirect', 'RedirectKeepVerb', 'BadRequest', 'Unauthorized', 'PaymentRequired', 'Forbidden', 'NotFound', 'MethodNotAllowed', 'NotAcceptable', 'ProxyAuthenticationRequired', 'RequestTimeout', 'Conflict', 'Gone', 'LengthRequired', 'PreconditionFailed', 'RequestEntityTooLarge', 'RequestUriTooLong', 'UnsupportedMediaType', 'RequestedRangeNotSatisfiable', 'ExpectationFailed', 'UpgradeRequired', 'InternalServerError', 'NotImplemented', 'BadGateway', 'ServiceUnavailable', 'GatewayTimeout', 'HttpVersionNotSupported'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>