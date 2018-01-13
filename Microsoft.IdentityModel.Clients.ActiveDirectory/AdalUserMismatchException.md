<Type Name="AdalUserMismatchException" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException">
  <TypeSignature Language="C#" Value="public class AdalUserMismatchException : Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdalUserMismatchException extends Microsoft.IdentityModel.Clients.ActiveDirectory.AdalException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdalUserMismatchException&#xA;Inherits AdalException" />
  <TypeSignature Language="F#" Value="type AdalUserMismatchException = class&#xA;    inherit AdalException" />
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
      <MemberSignature Language="C#" Value="public AdalUserMismatchException (string requestedUser, string returnedUser);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string requestedUser, string returnedUser) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (requestedUser As String, returnedUser As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException (requestedUser, returnedUser)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestedUser" Type="System.String" />
        <Parameter Name="returnedUser" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="requestedUser">To be added.</param>
        <param name="returnedUser">To be added.</param>
        <summary>
             Initialisiert eine neue Instanz der Exception-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedUser">
      <MemberSignature Language="C#" Value="public string RequestedUser { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.RequestedUser" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedUser As String" />
      <MemberSignature Language="F#" Value="member this.RequestedUser : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.RequestedUser" />
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
            Erhält der Benutzer, die vom Dienst angefordert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnedUser">
      <MemberSignature Language="C#" Value="public string ReturnedUser { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReturnedUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.ReturnedUser" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReturnedUser As String" />
      <MemberSignature Language="F#" Value="member this.ReturnedUser : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.ReturnedUser" />
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
            Erhält der Benutzer, die vom Dienst zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalUserMismatchException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="adalUserMismatchException.ToString " />
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