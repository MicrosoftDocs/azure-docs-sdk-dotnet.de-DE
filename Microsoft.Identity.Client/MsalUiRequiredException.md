<Type Name="MsalUiRequiredException" FullName="Microsoft.Identity.Client.MsalUiRequiredException">
  <TypeSignature Language="C#" Value="public class MsalUiRequiredException : Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MsalUiRequiredException extends Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.MsalUiRequiredException" />
  <TypeSignature Language="VB.NET" Value="Public Class MsalUiRequiredException&#xA;Inherits MsalException" />
  <TypeSignature Language="F#" Value="type MsalUiRequiredException = class&#xA;    inherit MsalException" />
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
            Diese Ausnahmeklasse besteht darin Entwickler zu informieren, die Interaktion mit der Benutzeroberfläche für die erfolgreiche Authentifizierung erforderlich ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalUiRequiredException (string errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalUiRequiredException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalUiRequiredException : string -&gt; Microsoft.Identity.Client.MsalUiRequiredException" Usage="new Microsoft.Identity.Client.MsalUiRequiredException errorCode" />
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
            Der Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalUiRequiredException (string errorCode, string errorMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalUiRequiredException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalUiRequiredException : string * string -&gt; Microsoft.Identity.Client.MsalUiRequiredException" Usage="new Microsoft.Identity.Client.MsalUiRequiredException (errorCode, errorMessage)" />
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
      <MemberSignature Language="C#" Value="public MsalUiRequiredException (string errorCode, string errorMessage, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalUiRequiredException.#ctor(System.String,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalUiRequiredException : string * string * Exception -&gt; Microsoft.Identity.Client.MsalUiRequiredException" Usage="new Microsoft.Identity.Client.MsalUiRequiredException (errorCode, errorMessage, innerException)" />
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
        <param name="innerException">Stellt die Ursache der Ausnahme.</param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode, Fehlermeldung und inneren Ausnahme, der angibt, der Ursache.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvalidGrantError">
      <MemberSignature Language="C#" Value="public static readonly string InvalidGrantError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string InvalidGrantError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.InvalidGrantError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly InvalidGrantError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable InvalidGrantError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.InvalidGrantError" />
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
            Standard OAuth2-Protokoll-Fehlercode. Er gibt an, die libray, dass der Benutzer, um die Benutzeroberfläche für die erste eines neuen Tokens zu wechseln muss.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoPromptFailedError">
      <MemberSignature Language="C#" Value="public static readonly string NoPromptFailedError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string NoPromptFailedError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.NoPromptFailedError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NoPromptFailedError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable NoPromptFailedError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.NoPromptFailedError" />
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
            Eine von zwei Bedingungen aufgetreten ist.
            1. Das Flag PromptBehavior.Never übergeben wurde und jedoch die Einschränkung konnte nicht berücksichtigt werden, da eine Benutzerinteraktion erforderlich war.
            2. Fehler bei einem automatischen Webauthentifizierung, die verhindert, dass der Authentifizierungsablauf abschließen in einen kurzen genügend Zeitraums ausgeführt wurden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoTokensFoundError">
      <MemberSignature Language="C#" Value="public static readonly string NoTokensFoundError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string NoTokensFoundError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.NoTokensFoundError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NoTokensFoundError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable NoTokensFoundError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.NoTokensFoundError" />
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
            Den Kriterien entspricht, ist keine Token gefunden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenCacheNullError">
      <MemberSignature Language="C#" Value="public static readonly string TokenCacheNullError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string TokenCacheNullError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.TokenCacheNullError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly TokenCacheNullError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable TokenCacheNullError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.TokenCacheNullError" />
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
            Mit diesem Fehlercode stammt wieder aus AcquireTokenSilent aufrufen, wenn der Tokencache null-Verweis an den Anwendungskonstruktor übergeben wird
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserNullError">
      <MemberSignature Language="C#" Value="public static readonly string UserNullError;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly string UserNullError" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalUiRequiredException.UserNullError" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly UserNullError As String " />
      <MemberSignature Language="F#" Value=" staticval mutable UserNullError : string" Usage="Microsoft.Identity.Client.MsalUiRequiredException.UserNullError" />
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
            Mit diesem Fehlercode stammt AcquireTokenSilent Aufrufe zurück, wenn null-Benutzer in AcquireTokenSilent Aufrufe übergeben wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>