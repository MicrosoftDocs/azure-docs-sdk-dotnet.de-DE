<Type Name="MsalClientException" FullName="Microsoft.Identity.Client.MsalClientException">
  <TypeSignature Language="C#" Value="public class MsalClientException : Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MsalClientException extends Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.MsalClientException" />
  <TypeSignature Language="VB.NET" Value="Public Class MsalClientException&#xA;Inherits MsalException" />
  <TypeSignature Language="F#" Value="type MsalClientException = class&#xA;    inherit MsalException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Identity.Client.MsalException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Ausnahmeklasse stellt Fehler, die für die Bibliothek oder das Gerät lokal sind.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalClientException (string errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalClientException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalClientException : string -&gt; Microsoft.Identity.Client.MsalClientException" Usage="new Microsoft.Identity.Client.MsalClientException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            Der Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.</param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalClientException (string errorCode, string errorMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalClientException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalClientException : string * string -&gt; Microsoft.Identity.Client.MsalClientException" Usage="new Microsoft.Identity.Client.MsalClientException (errorCode, errorMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            Der Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </param>
        <param name="errorMessage">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode und eine Fehlermeldung an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalClientException (string errorCode, string errorMessage, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalClientException.#ctor(System.String,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalClientException : string * string * Exception -&gt; Microsoft.Identity.Client.MsalClientException" Usage="new Microsoft.Identity.Client.MsalClientException (errorCode, errorMessage, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            Der Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </param>
        <param name="errorMessage">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <param name="innerException"></param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einer angegebenen Fehlercode, der Fehlermeldung und der inneren Ausnahme.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationCanceledError">
      <MemberSignature Language="C#" Value="public const string AuthenticationCanceledError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AuthenticationCanceledError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.AuthenticationCanceledError" />
      <MemberSignature Language="VB.NET" Value="Public Const AuthenticationCanceledError As String " />
      <MemberSignature Language="F#" Value="val mutable AuthenticationCanceledError : string" Usage="Microsoft.Identity.Client.MsalClientException.AuthenticationCanceledError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Authentifizierung abgebrochen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationUiFailedError">
      <MemberSignature Language="C#" Value="public const string AuthenticationUiFailedError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AuthenticationUiFailedError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.AuthenticationUiFailedError" />
      <MemberSignature Language="VB.NET" Value="Public Const AuthenticationUiFailedError As String " />
      <MemberSignature Language="F#" Value="val mutable AuthenticationUiFailedError : string" Usage="Microsoft.Identity.Client.MsalClientException.AuthenticationUiFailedError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Anforderung konnte aufgrund eines Fehlers in der UI-Fluss nicht durchgeführt werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateQueryParameterError">
      <MemberSignature Language="C#" Value="public const string DuplicateQueryParameterError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DuplicateQueryParameterError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.DuplicateQueryParameterError" />
      <MemberSignature Language="VB.NET" Value="Public Const DuplicateQueryParameterError As String " />
      <MemberSignature Language="F#" Value="val mutable DuplicateQueryParameterError : string" Usage="Microsoft.Identity.Client.MsalClientException.DuplicateQueryParameterError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Doppelte Abfrageparameter in extraQueryParameters
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvalidJwtError">
      <MemberSignature Language="C#" Value="public const string InvalidJwtError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string InvalidJwtError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.InvalidJwtError" />
      <MemberSignature Language="VB.NET" Value="Public Const InvalidJwtError As String " />
      <MemberSignature Language="F#" Value="val mutable InvalidJwtError : string" Usage="Microsoft.Identity.Client.MsalClientException.InvalidJwtError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            JWT war ungültig.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonParseError">
      <MemberSignature Language="C#" Value="public const string JsonParseError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string JsonParseError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.JsonParseError" />
      <MemberSignature Language="VB.NET" Value="Public Const JsonParseError As String " />
      <MemberSignature Language="F#" Value="val mutable JsonParseError : string" Usage="Microsoft.Identity.Client.MsalClientException.JsonParseError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Fehler bei der Analyse von JSON.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultipleTokensMatchedError">
      <MemberSignature Language="C#" Value="public const string MultipleTokensMatchedError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MultipleTokensMatchedError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.MultipleTokensMatchedError" />
      <MemberSignature Language="VB.NET" Value="Public Const MultipleTokensMatchedError As String " />
      <MemberSignature Language="F#" Value="val mutable MultipleTokensMatchedError : string" Usage="Microsoft.Identity.Client.MsalClientException.MultipleTokensMatchedError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            MultipleTokensMatched abgeglichen wurden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkNotAvailableError">
      <MemberSignature Language="C#" Value="public const string NetworkNotAvailableError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string NetworkNotAvailableError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.NetworkNotAvailableError" />
      <MemberSignature Language="VB.NET" Value="Public Const NetworkNotAvailableError As String " />
      <MemberSignature Language="F#" Value="val mutable NetworkNotAvailableError : string" Usage="Microsoft.Identity.Client.MsalClientException.NetworkNotAvailableError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Anforderung konnte nicht durchgeführt werden, da das Netzwerk ausgefallen ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NonHttpsRedirectNotSupported">
      <MemberSignature Language="C#" Value="public const string NonHttpsRedirectNotSupported;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string NonHttpsRedirectNotSupported" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.NonHttpsRedirectNotSupported" />
      <MemberSignature Language="VB.NET" Value="Public Const NonHttpsRedirectNotSupported As String " />
      <MemberSignature Language="F#" Value="val mutable NonHttpsRedirectNotSupported : string" Usage="Microsoft.Identity.Client.MsalClientException.NonHttpsRedirectNotSupported" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Nicht HTTPS umgeleitet werden nicht unterstützt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateMismatchError">
      <MemberSignature Language="C#" Value="public const string StateMismatchError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string StateMismatchError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.StateMismatchError" />
      <MemberSignature Language="VB.NET" Value="Public Const StateMismatchError As String " />
      <MemberSignature Language="F#" Value="val mutable StateMismatchError : string" Usage="Microsoft.Identity.Client.MsalClientException.StateMismatchError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Status von den STS zurückgegebenen wurde unterscheiden, die gesendet.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantDiscoveryFailedError">
      <MemberSignature Language="C#" Value="public const string TenantDiscoveryFailedError;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string TenantDiscoveryFailedError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalClientException.TenantDiscoveryFailedError" />
      <MemberSignature Language="VB.NET" Value="Public Const TenantDiscoveryFailedError As String " />
      <MemberSignature Language="F#" Value="val mutable TenantDiscoveryFailedError : string" Usage="Microsoft.Identity.Client.MsalClientException.TenantDiscoveryFailedError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Fehler bei der Ermittlung des Mandanten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>