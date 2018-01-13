<Type Name="OperationWorkerResponse" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse">
  <TypeSignature Language="C#" Value="public class OperationWorkerResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationWorkerResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationWorkerResponse" />
  <TypeSignature Language="F#" Value="type OperationWorkerResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Dies ist die Basisklasse für Ergebnis Vorgangsantworten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationWorkerResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der OperationWorkerResponse-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationWorkerResponse (Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; statusCode = null, System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; headers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; statusCode, class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; headers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.#ctor(System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode},System.Collections.Generic.IDictionary{System.String,System.Collections.Generic.IList{System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional statusCode As Nullable(Of HttpStatusCode) = null, Optional headers As IDictionary(Of String, IList(Of String)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; * System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse (statusCode, headers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="statusCode" Type="System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt;" />
        <Parameter Name="headers" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="statusCode">HTTP-Statuscode des Vorgangs.
            Folgende Werte sind möglich: "Continue", "SwitchingProtocols", "OK", "Created", "Akzeptiert", "NonAuthoritativeInformation", "NoContent", "ResetContent", "PartialContent", "MultipleChoices',"Mehrdeutig","MovedPermanently","Verschoben","Gefunden,"" Umleiten ","SeeOther","RedirectMethod","NotModified","UseProxy","Nicht verwendet","TemporaryRedirect","RedirectKeepVerb","BadRequest","nicht autorisiert","PaymentRequired","Unzulässig","NotFound","MethodNotAllowed","Antwortformat"," ProxyAuthenticationRequired', 'RequestTimeout', "In Konflikt stehen", "Weg", "Length", "Dass die Streamingendpunkteigenschaft", "RequestEntityTooLarge", "RequestUriTooLong", "UnsupportedMediaType", "RequestedRangeNotSatisfiable", "ExpectationFailed", " UpgradeRequired ","InternalServerError","NotImplemented","BadGateway","ServiceUnavailable","GatewayTimeout","HttpVersionNotSupported"</param>
        <param name="headers">Diesem Vorgang zugeordneten HTTP-Header.</param>
        <summary>
            Initialisiert eine neue Instanz der OperationWorkerResponse-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,System.Collections.Generic.IList&lt;string&gt;&gt; Headers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class System.Collections.Generic.IList`1&lt;string&gt;&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.Headers" />
      <MemberSignature Language="VB.NET" Value="Public Property Headers As IDictionary(Of String, IList(Of String))" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, System.Collections.Generic.IList&lt;string&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Headers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Collections.Generic.IList&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert diesen Vorgang zugeordneten HTTP-Header.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As Nullable(Of HttpStatusCode)" />
      <MemberSignature Language="F#" Value="member this.StatusCode : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationWorkerResponse.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.HttpStatusCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die HTTP-Statuscode des Vorgangs. Folgende Werte sind möglich: "Continue", "SwitchingProtocols", "OK", "Created", "Akzeptiert", "NonAuthoritativeInformation", "NoContent", "ResetContent", "PartialContent", "MultipleChoices',"Mehrdeutig","MovedPermanently","Verschoben","Gefunden,"" Umleiten ","SeeOther","RedirectMethod","NotModified","UseProxy","Nicht verwendet","TemporaryRedirect","RedirectKeepVerb","BadRequest","nicht autorisiert","PaymentRequired","Unzulässig","NotFound","MethodNotAllowed","Antwortformat"," ProxyAuthenticationRequired', 'RequestTimeout', "In Konflikt stehen", "Weg", "Length", "Dass die Streamingendpunkteigenschaft", "RequestEntityTooLarge", "RequestUriTooLong", "UnsupportedMediaType", "RequestedRangeNotSatisfiable", "ExpectationFailed", " UpgradeRequired ","InternalServerError","NotImplemented","BadGateway","ServiceUnavailable","GatewayTimeout","HttpVersionNotSupported"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>