<Type Name="AdalException" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException">
  <TypeSignature Language="C#" Value="public class AdalException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdalException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdalException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type AdalException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Ausnahmetyp ausgelöst, wenn ein Fehler während der tokenabruf auftritt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
             Initialisiert eine neue Instanz der Exception-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalException (string errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException : string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">Der Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.</param>
        <summary>
             Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalException (string errorCode, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException : string * Exception -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException (errorCode, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">Der Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.</param>
        <param name="innerException">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird. Es kann insbesondere die eigentlichen Fehlermeldung, die vom Dienst zurückgegebenen enthalten.</param>
        <summary>
             Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalException (string errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException (errorCode, message)" />
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
        <param name="errorCode">Der Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.</param>
        <param name="message">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <summary>
             Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode und eine Fehlermeldung an.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalException (string errorCode, string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.#ctor(System.String,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException : string * string * Exception -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException (errorCode, message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="errorCode">Der Fehlercode vom Dienst zurückgegeben wurde oder vom Client generiert. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.</param>
        <param name="message">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</param>
        <param name="innerException">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird. Es kann insbesondere die eigentlichen Fehlermeldung, die vom Dienst zurückgegebenen enthalten.</param>
        <summary>
             Initialisiert eine neue Instanz der Exception-Klasse mit einem angegebenen Fehlercode, der Fehlermeldung und einen Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public string ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As String" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Fehlercode Protokoll vom Dienst zurückgegeben wurde, oder vom Client generiert wird. Dies ist der Code, den Sie für die Ausnahmebehandlung auf verlassen können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="adalException.ToString " />
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