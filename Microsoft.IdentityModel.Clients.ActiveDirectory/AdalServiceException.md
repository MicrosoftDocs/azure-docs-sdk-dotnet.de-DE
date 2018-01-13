<Type Name="AdalServiceException" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException">
  <TypeSignature Language="C#" Value="public class AdalServiceException : Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdalServiceException extends Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdalServiceException&#xA;Inherits AdalException" />
  <TypeSignature Language="F#" Value="type AdalServiceException = class&#xA;    inherit AdalException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Typ der Ausnahme wird ausgelöst, wenn der Benutzer vom Dienst zurückgegebenen stimmt nicht mit Benutzer in der Anforderung überein.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalServiceException (string errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException (errorCode, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">Die Protokoll-Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.</param>
        <param name="message">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <summary>
             Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode und eine Fehlermeldung an.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Net.Http.Headers.HttpResponseHeaders Headers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.Http.Headers.HttpResponseHeaders Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.Headers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Headers As HttpResponseHeaders" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Net.Http.Headers.HttpResponseHeaders" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.Http.Headers.HttpResponseHeaders</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Enthält der Header aus der Antwort, die einen Fehler angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceErrorCodes">
      <MemberSignature Language="C#" Value="public string[] ServiceErrorCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] ServiceErrorCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.ServiceErrorCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceErrorCodes As String()" />
      <MemberSignature Language="F#" Value="member this.ServiceErrorCodes : string[] with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.ServiceErrorCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die bestimmte Fehlercodes, die vom Dienst zurückgegeben werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public int StatusCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.StatusCode : int with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="adalServiceException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
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