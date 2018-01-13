<Type Name="CustomHeaderConstants" FullName="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants">
  <TypeSignature Language="C#" Value="public static class CustomHeaderConstants" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CustomHeaderConstants extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomHeaderConstants" />
  <TypeSignature Language="F#" Value="type CustomHeaderConstants = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Ack">
      <MemberSignature Language="C#" Value="public const string Ack;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Ack" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.Ack" />
      <MemberSignature Language="VB.NET" Value="Public Const Ack As String " />
      <MemberSignature Language="F#" Value="val mutable Ack : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.Ack" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [Optional] Wird verwendet, um das Feedback für den Verbrauch der Nachricht erforderlich sind, von dem Gerät anzugeben. Mögliche Werte: "none": kein Feedback "Positive": eine Feedback Meldung, wenn die Meldung "negative" verwendet wurde: eine Feedback Meldung, wenn die Nachricht abgelaufen, ohne das Gerät "Full" ausgeführt wird: positive und negative
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityId">
      <MemberSignature Language="C#" Value="public const string ActivityId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ActivityId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ActivityId" />
      <MemberSignature Language="VB.NET" Value="Public Const ActivityId As String " />
      <MemberSignature Language="F#" Value="val mutable ActivityId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ActivityId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Aktivität-Id der Wert, der zum Übergeben von "ActivityId" in REST-API zwischen Diensten verwendet wird
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public const string ApiVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ApiVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ApiVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ApiVersion : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ApiVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            API-Version gibt die Version des für diese Anforderung verwendeten Protokolls.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAppId">
      <MemberSignature Language="C#" Value="public const string ClientAppId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientAppId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientAppId" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientAppId As String " />
      <MemberSignature Language="F#" Value="val mutable ClientAppId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientAppId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Client-app-Id-Satz für die app-Id des JWT anfordernde Clients.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAudience">
      <MemberSignature Language="C#" Value="public const string ClientAudience;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientAudience" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientAudience" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientAudience As String " />
      <MemberSignature Language="F#" Value="val mutable ClientAudience : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientAudience" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Richten Sie X-ms-Client-Zielgruppe so die Mandanten-ID des JWT anfordernde Clients.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientIpAddress">
      <MemberSignature Language="C#" Value="public const string ClientIpAddress;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientIpAddress" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientIpAddress As String " />
      <MemberSignature Language="F#" Value="val mutable ClientIpAddress : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientIpAddress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Client-Ip-Adresse, die auf die Client-IP-Adresse in der Anforderung verwendete festgelegt werden; Dies ist erforderlich, da der Ressourcenanbieter keinen Zugriff auf die Client-IP-Adresse wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientIssuer">
      <MemberSignature Language="C#" Value="public const string ClientIssuer;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientIssuer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientIssuer" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientIssuer As String " />
      <MemberSignature Language="F#" Value="val mutable ClientIssuer : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientIssuer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Client-Aussteller Satz an den Aussteller des JWT anfordernde Clients.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientObjectId">
      <MemberSignature Language="C#" Value="public const string ClientObjectId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientObjectId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientObjectId As String " />
      <MemberSignature Language="F#" Value="val mutable ClientObjectId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientObjectId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Client-Objekt-Id-Satz mit dem Objekt-Id des JWT anfordernde Clients.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public const string ClientRequestId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientRequestId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientRequestId As String " />
      <MemberSignature Language="F#" Value="val mutable ClientRequestId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientRequestId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Client-Request-Id aufruferspezifische Anforderungs-ID, in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern (z. B. Client-Request-Id: 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0). Ein vom Aufrufer definierter Wert, der die angegebene Anforderung identifiziert.   Falls angegeben, wird dieser Wert in die Antwortinformationen eingeschlossen, um die Anforderung zuordnen zu können. Wenn der Aufrufer dieses Headers – den Ressourcenanbieter bietet *müssen* melden Sie dies mit ihren ablaufverfolgungen zur Erleichterung der Ablaufverfolgung für einer einzelnen Anforderung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientTenantId">
      <MemberSignature Language="C#" Value="public const string ClientTenantId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ClientTenantId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientTenantId" />
      <MemberSignature Language="VB.NET" Value="Public Const ClientTenantId As String " />
      <MemberSignature Language="F#" Value="val mutable ClientTenantId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ClientTenantId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Client-Mandanten-Id, die auf die Mandanten-ID des JWT anfordernde Clients festgelegt werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public const string CorrelationId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string CorrelationId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Const CorrelationId As String " />
      <MemberSignature Language="F#" Value="val mutable CorrelationId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.CorrelationId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Verwendet Message Antworten und Feedback gibt die ablaufverfolgungskorrelations-Id für die Anforderung; der Ressourcenanbieter *müssen* dies protokolliert werden, damit End-to-End-Anforderungen innerhalb von Azure korreliert werden können. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public const string DeliveryCount;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DeliveryCount" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Const DeliveryCount As String " />
      <MemberSignature Language="F#" Value="val mutable DeliveryCount : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.DeliveryCount" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Anzahl der Häufigkeit, mit der die Nachricht zuvor übermittelt wurden
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTime">
      <MemberSignature Language="C#" Value="public const string EnqueuedTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string EnqueuedTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.EnqueuedTime" />
      <MemberSignature Language="VB.NET" Value="Public Const EnqueuedTime As String " />
      <MemberSignature Language="F#" Value="val mutable EnqueuedTime : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.EnqueuedTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Uhrzeit, wann die Nachricht vom Server empfangen wurde
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public const string ExpiryTime;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ExpiryTime" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Const ExpiryTime As String " />
      <MemberSignature Language="F#" Value="val mutable ExpiryTime : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ExpiryTime" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [Optional] Die Zeit, wenn diese Meldung berücksichtigt ist, abgelaufen
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpAppPropertyPrefix">
      <MemberSignature Language="C#" Value="public const string HttpAppPropertyPrefix;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpAppPropertyPrefix" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpAppPropertyPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpAppPropertyPrefix As String " />
      <MemberSignature Language="F#" Value="val mutable HttpAppPropertyPrefix : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpAppPropertyPrefix" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Präfix für alle Anwendungseigenschaft HTTP-Header
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpDevice">
      <MemberSignature Language="C#" Value="public const string HttpDevice;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpDevice" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpDevice" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpDevice As String " />
      <MemberSignature Language="F#" Value="val mutable HttpDevice : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpDevice" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpErrorCodeName">
      <MemberSignature Language="C#" Value="public const string HttpErrorCodeName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpErrorCodeName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpErrorCodeName" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpErrorCodeName As String " />
      <MemberSignature Language="F#" Value="val mutable HttpErrorCodeName : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpErrorCodeName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpIotHub">
      <MemberSignature Language="C#" Value="public const string HttpIotHub;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpIotHub" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpIotHub" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpIotHub As String " />
      <MemberSignature Language="F#" Value="val mutable HttpIotHub : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpIotHub" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpIotHubName">
      <MemberSignature Language="C#" Value="public const string HttpIotHubName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpIotHubName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpIotHubName" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpIotHubName As String " />
      <MemberSignature Language="F#" Value="val mutable HttpIotHubName : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.HttpIotHubName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Interne benutzerdefinierte HTTP-Header
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public const string MessageId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MessageId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Const MessageId As String " />
      <MemberSignature Language="F#" Value="val mutable MessageId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [Erforderlich für zwei Weise, wie Anforderungen] Verwendet, um bidirektionale Kommunikation zu korrelieren. : Ein Groß-/Kleinschreibung Formatzeichenfolge (bis zu 128 Zeichen lang) der alphanumerische ASCII-7-Bit-Zeichen
            + {'-', ':', '/', '\', '.', '+', '%', '_', '#', '*', '?', '!', '(', ')', ',', '=', '@', ';', '$', '''}. Nicht alphanumerische Zeichen sind in RFC URN.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageLockTimeout">
      <MemberSignature Language="C#" Value="public const string MessageLockTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MessageLockTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageLockTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Const MessageLockTimeout As String " />
      <MemberSignature Language="F#" Value="val mutable MessageLockTimeout : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageLockTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Zeitdauer in Sekunden für die Nachricht zu löschen, bevor die Sperre aufgeben und ermöglicht die Nachricht erneut abgerufen werden sollen
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageLockToken">
      <MemberSignature Language="C#" Value="public const string MessageLockToken;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MessageLockToken" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageLockToken" />
      <MemberSignature Language="VB.NET" Value="Public Const MessageLockToken As String " />
      <MemberSignature Language="F#" Value="val mutable MessageLockToken : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MessageLockToken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Sperrtoken der abgerufenen Nachricht 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftAsyncOperationHeaderName">
      <MemberSignature Language="C#" Value="public const string MicrosoftAsyncOperationHeaderName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MicrosoftAsyncOperationHeaderName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MicrosoftAsyncOperationHeaderName" />
      <MemberSignature Language="VB.NET" Value="Public Const MicrosoftAsyncOperationHeaderName As String " />
      <MemberSignature Language="F#" Value="val mutable MicrosoftAsyncOperationHeaderName : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.MicrosoftAsyncOperationHeaderName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure-AsyncOperation legen die URL, in denen das Ergebnis des Vorgangs mit langer überprüft werden kann; Zusätzlich zu den Location-Header optional verwendet werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public const string Operation;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Operation" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Const Operation As String " />
      <MemberSignature Language="F#" Value="val mutable Operation : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.Operation" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [Optional] Wird verwendet, um die Rolle der Nachricht in das Kommunikationsmuster anzugeben. Mögliche Werte: "d2c": Telemetrie-Nachricht (Gerät in der cloud) "c2d": Benachrichtigung "d2creq": Anfrage Anforderung "d2cres": eine Anfrage-Antwort "c2dreq": befehlsanforderung "c2dres": Befehl Antwort
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalName">
      <MemberSignature Language="C#" Value="public const string PrincipalName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string PrincipalName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.PrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Const PrincipalName As String " />
      <MemberSignature Language="F#" Value="val mutable PrincipalName : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.PrincipalName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Client-Prinzipal-Name auf dem Prinzipal-ID festgelegt / UPN des JWT-Clients Ausführen der Anforderung verwendet werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public const string RequestId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RequestId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Const RequestId As String " />
      <MemberSignature Language="F#" Value="val mutable RequestId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.RequestId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            X-ms-Request-Id ein eindeutiger Bezeichner für den aktuellen Vorgang, Dienst generiert.
            Alle Ressourcenanbieter *müssen* dieser Rückgabewert in die Antwortheader, um Debuggen zu vereinfachen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public const string ReturnClientRequestId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Const ReturnClientRequestId As String " />
      <MemberSignature Language="F#" Value="val mutable ReturnClientRequestId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.ReturnClientRequestId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            x-ms-Return-Client-Request-ID Optional "true" oder "false" und gibt an, ob eine Client-Request-Id bereitgestellt werden muss.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public const string SequenceNumber;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string SequenceNumber" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const SequenceNumber As String " />
      <MemberSignature Language="F#" Value="val mutable SequenceNumber : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.SequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine monoton ansteigende Bezeichner für jede Nachricht Iothub-sequencenumber
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public const string To;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string To" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.To" />
      <MemberSignature Language="VB.NET" Value="Public Const To As String " />
      <MemberSignature Language="F#" Value="val mutable To : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.To" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [Erforderlich] Ziel der Nachricht
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public const string UserId;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string UserId" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Const UserId As String " />
      <MemberSignature Language="F#" Value="val mutable UserId : string" Usage="Microsoft.Azure.Devices.Common.WebApi.CustomHeaderConstants.UserId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            [In Feedback Nachrichten erforderlich] Dient zum Angeben des Ursprungs von Nachrichten durch den IOT Hub generiert. Wert: "{Hub-Name} /"
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>