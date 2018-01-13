<Type Name="MsalServiceException" FullName="Microsoft.Identity.Client.MsalServiceException">
  <TypeSignature Language="C#" Value="public class MsalServiceException : Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MsalServiceException extends Microsoft.Identity.Client.MsalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.MsalServiceException" />
  <TypeSignature Language="VB.NET" Value="Public Class MsalServiceException&#xA;Inherits MsalException" />
  <TypeSignature Language="F#" Value="type MsalServiceException = class&#xA;    inherit MsalException" />
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
            Der Typ der Ausnahme wird ausgelöst, wenn der Dienst zurückgibt und Fehlerantwort oder andere Netzwerkfehler auftreten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage)" />
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
            Die Protokoll-Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </param>
        <param name="errorMessage">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode, der Fehlermeldung und einen Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string * Exception -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage, innerException)" />
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
            Die Protokoll-Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </param>
        <param name="errorMessage">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <param name="innerException">
            Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.
            </param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode, der Fehlermeldung und einen Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage, int statusCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, int32 statusCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, statusCode As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string * int -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage, statusCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="statusCode" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            Die Protokoll-Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </param>
        <param name="errorMessage">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <param name="statusCode">Der Statuscode der die vom Dienst empfangenen Umleitungszeichenfolge.</param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode, der Fehlermeldung und einen Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage, int statusCode, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, int32 statusCode, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String,System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, statusCode As Integer, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string * int * Exception -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage, statusCode, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            Die Protokoll-Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </param>
        <param name="errorMessage">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <param name="statusCode">Der Statuscode der die vom Dienst empfangenen Umleitungszeichenfolge.</param>
        <param name="innerException">
            Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.
            </param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode, der Fehlermeldung und einen Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MsalServiceException (string errorCode, string errorMessage, int statusCode, string claims, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string errorMessage, int32 statusCode, string claims, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.#ctor(System.String,System.String,System.Int32,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, errorMessage As String, statusCode As Integer, claims As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.MsalServiceException : string * string * int * string * Exception -&gt; Microsoft.Identity.Client.MsalServiceException" Usage="new Microsoft.Identity.Client.MsalServiceException (errorCode, errorMessage, statusCode, claims, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="claims" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">
            Die Protokoll-Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </param>
        <param name="errorMessage">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <param name="statusCode">Der Statuscode der Anforderung.</param>
        <param name="claims">Die Ansprüche-Abfrage zurückgegebenen wieder aus dem Dienst.</param>
        <param name="innerException">
            Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.
            </param>
        <summary>
            Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode, der Fehlermeldung und einen Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Claims">
      <MemberSignature Language="C#" Value="public string Claims { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Claims" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.MsalServiceException.Claims" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Claims As String" />
      <MemberSignature Language="F#" Value="member this.Claims : string" Usage="Microsoft.Identity.Client.MsalServiceException.Claims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTimeout">
      <MemberSignature Language="C#" Value="public const string RequestTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RequestTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalServiceException.RequestTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Const RequestTimeout As String " />
      <MemberSignature Language="F#" Value="val mutable RequestTimeout : string" Usage="Microsoft.Identity.Client.MsalServiceException.RequestTimeout" />
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
            Timeout bei der HTTP-Anforderung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseBody">
      <MemberSignature Language="C#" Value="public string ResponseBody { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResponseBody" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.MsalServiceException.ResponseBody" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResponseBody As String" />
      <MemberSignature Language="F#" Value="member this.ResponseBody : string" Usage="Microsoft.Identity.Client.MsalServiceException.ResponseBody" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Unformatierte Antworttext vom Server empfangen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNotAvailable">
      <MemberSignature Language="C#" Value="public const string ServiceNotAvailable;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ServiceNotAvailable" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.MsalServiceException.ServiceNotAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Const ServiceNotAvailable As String " />
      <MemberSignature Language="F#" Value="val mutable ServiceNotAvailable : string" Usage="Microsoft.Identity.Client.MsalServiceException.ServiceNotAvailable" />
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
            Dienst nicht verfügbar ist und HTTP-Fehlercode innerhalb des Bereichs von 500 599 zurückgegeben.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public int StatusCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.MsalServiceException.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.StatusCode : int" Usage="Microsoft.Identity.Client.MsalServiceException.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Statuscode von HTTP-Ebene zurückgegeben. Dieser Statuscode wird entweder der HttpStatusCode in der inneren HttpRequestException Antwort oder NavigateError Ereignis Statuscode im Browser basierten Fluss (siehe http://msdn.microsoft.com/en-us/library/bb268233 (v=vs.85).aspx).
            Sie können diesen Code für Zwecke wie der Wiederholung Logik oder Fehler Untersuchung implementieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.MsalServiceException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="msalServiceException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Zeichenfolgendarstellung der aktuellen Ausnahme und gibt diese zurück.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der aktuellen Ausnahme.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>