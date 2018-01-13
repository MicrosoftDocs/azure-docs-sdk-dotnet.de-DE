<Type Name="AuthorizationSession" FullName="Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession">
  <TypeSignature Language="C#" Value="public class AuthorizationSession" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthorizationSession extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthorizationSession" />
  <TypeSignature Language="F#" Value="type AuthorizationSession = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Sitzung für OAuth Authorization wird verwendet, um den Authorization Code Grant-Datenfluss zum Zulassen von ADF für den Zugriff auf Ressourcen in Ihrem Auftrag zu initiieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AuthorizationSession-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationSession (Uri endpoint, string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri endpoint, string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpoint As Uri, sessionId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession : Uri * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession" Usage="new Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession (endpoint, sessionId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpoint">To be added.</param>
        <param name="sessionId">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der AuthorizationSession-Klasse mit erforderlichen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Verwenden Sie die OAuth-autorisierungsendpunkt anmelden und Abrufen einer Autorisierungs, die Zugriff auf Ressourcen in Ihrem Auftrag von ADF verwendet werden kann. Jede Autorisierung ist eindeutig und kann nur einmal verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AuthorizationSession.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Geben Sie diesen Wert beim Erstellen einer OAuth Dienst verknüpfte.
            Jede Sitzungs-ID ist eindeutig und darf nur einmal verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>