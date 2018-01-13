<Type Name="OperationResultInfoBaseResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource">
  <TypeSignature Language="C#" Value="public class OperationResultInfoBaseResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationResultInfoBaseResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationResultInfoBaseResource&#xA;Inherits OperationWorkerResponse" />
  <TypeSignature Language="F#" Value="type OperationResultInfoBaseResource = class&#xA;    inherit OperationWorkerResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e9e41-101">Die Basisklasse für Vorgang Ergebnis Info.</span><span class="sxs-lookup"><span data-stu-id="e9e41-101">Base class for operation result info.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResultInfoBaseResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e9e41-102">Initialisiert eine neue Instanz der OperationResultInfoBaseResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e9e41-102">Initializes a new instance of the OperationResultInfoBaseResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationResultInfoBaseResource (Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; statusCode = null, System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; headers = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase operation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; statusCode, class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; headers, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource.#ctor(System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode},System.Collections.Generic.IDictionary{System.String,System.Collections.Generic.IList{System.String}},Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional statusCode As Nullable(Of HttpStatusCode) = null, Optional headers As IDictionary(Of String, IList(Of String)) = null, Optional operation As OperationResultInfoBase = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; * System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource (statusCode, headers, operation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="statusCode" Type="System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt;" />
        <Parameter Name="headers" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;" />
        <Parameter Name="operation" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase" />
      </Parameters>
      <Docs>
        <param name="statusCode"><span data-ttu-id="e9e41-103">HTTP-Statuscode des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e9e41-103">HTTP Status Code of the operation.</span></span>
            <span data-ttu-id="e9e41-104">Folgende Werte sind möglich: "Continue", "SwitchingProtocols", "OK", "Created", "Akzeptiert", "NonAuthoritativeInformation", "NoContent", "ResetContent", "PartialContent", "MultipleChoices',"Mehrdeutig","MovedPermanently","Verschoben","Gefunden,"" Umleiten ","SeeOther","RedirectMethod","NotModified","UseProxy","Nicht verwendet","TemporaryRedirect","RedirectKeepVerb","BadRequest","nicht autorisiert","PaymentRequired","Unzulässig","NotFound","MethodNotAllowed","Antwortformat"," ProxyAuthenticationRequired', 'RequestTimeout', "In Konflikt stehen", "Weg", "Length", "Dass die Streamingendpunkteigenschaft", "RequestEntityTooLarge", "RequestUriTooLong", "UnsupportedMediaType", "RequestedRangeNotSatisfiable", "ExpectationFailed", " UpgradeRequired ","InternalServerError","NotImplemented","BadGateway","ServiceUnavailable","GatewayTimeout","HttpVersionNotSupported"</span><span class="sxs-lookup"><span data-stu-id="e9e41-104">Possible values include: 'Continue', 'SwitchingProtocols', 'OK', 'Created', 'Accepted', 'NonAuthoritativeInformation', 'NoContent', 'ResetContent', 'PartialContent', 'MultipleChoices', 'Ambiguous', 'MovedPermanently', 'Moved', 'Found', 'Redirect', 'SeeOther', 'RedirectMethod', 'NotModified', 'UseProxy', 'Unused', 'TemporaryRedirect', 'RedirectKeepVerb', 'BadRequest', 'Unauthorized', 'PaymentRequired', 'Forbidden', 'NotFound', 'MethodNotAllowed', 'NotAcceptable', 'ProxyAuthenticationRequired', 'RequestTimeout', 'Conflict', 'Gone', 'LengthRequired', 'PreconditionFailed', 'RequestEntityTooLarge', 'RequestUriTooLong', 'UnsupportedMediaType', 'RequestedRangeNotSatisfiable', 'ExpectationFailed', 'UpgradeRequired', 'InternalServerError', 'NotImplemented', 'BadGateway', 'ServiceUnavailable', 'GatewayTimeout', 'HttpVersionNotSupported'</span></span></param>
        <param name="headers"><span data-ttu-id="e9e41-105">Diesem Vorgang zugeordneten HTTP-Header.</span><span class="sxs-lookup"><span data-stu-id="e9e41-105">HTTP headers associated with this operation.</span></span></param>
        <param name="operation"><span data-ttu-id="e9e41-106">OperationResultInfoBaseResource Vorgang</span><span class="sxs-lookup"><span data-stu-id="e9e41-106">OperationResultInfoBaseResource operation</span></span></param>
        <summary>
            <span data-ttu-id="e9e41-107">Initialisiert eine neue Instanz der OperationResultInfoBaseResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e9e41-107">Initializes a new instance of the OperationResultInfoBaseResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As OperationResultInfoBase" />
      <MemberSignature Language="F#" Value="member this.Operation : Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBaseResource.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationResultInfoBase</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9e41-108">Ruft ab oder legt ihn fest OperationResultInfoBaseResource Vorgang</span><span class="sxs-lookup"><span data-stu-id="e9e41-108">Gets or sets operationResultInfoBaseResource operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>