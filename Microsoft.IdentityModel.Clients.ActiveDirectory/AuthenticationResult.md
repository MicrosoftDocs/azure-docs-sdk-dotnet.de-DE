<Type Name="AuthenticationResult" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationResult" />
  <TypeSignature Language="F#" Value="type AuthenticationResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Enthält die Ergebnisse von einem tokenabruf-Vorgang. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessToken">
      <MemberSignature Language="C#" Value="public string AccessToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.AccessToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessToken As String" />
      <MemberSignature Language="F#" Value="member this.AccessToken : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.AccessToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Zugriffstoken angefordert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTokenType">
      <MemberSignature Language="C#" Value="public string AccessTokenType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessTokenType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.AccessTokenType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessTokenType As String" />
      <MemberSignature Language="F#" Value="member this.AccessTokenType : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.AccessTokenType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des Zugriffstokens zurückgegeben. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthorizationHeader">
      <MemberSignature Language="C#" Value="public string CreateAuthorizationHeader ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string CreateAuthorizationHeader() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.CreateAuthorizationHeader" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAuthorizationHeader () As String" />
      <MemberSignature Language="F#" Value="member this.CreateAuthorizationHeader : unit -&gt; string" Usage="authenticationResult.CreateAuthorizationHeader " />
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
            Erstellt ein Autorisierungsheader aus Authentifizierungsergebnis.
            </summary>
        <returns>Erstellte Authorization-header</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOn">
      <MemberSignature Language="C#" Value="public DateTimeOffset ExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset ExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.ExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresOn As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.ExpiresOn : DateTimeOffset" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.ExpiresOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab dem Punkt in dem das Zugriffstoken in der AccessToken-Eigenschaft zurückgegeben wird nicht mehr gültig ist.
            Dieser Wert wird basierend auf dem aktuellen UTC-Zeit, die lokal gemessen und die vom Dienst empfangenen Wert ExpiresIn berechnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedLifeTimeToken">
      <MemberSignature Language="C#" Value="public bool ExtendedLifeTimeToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExtendedLifeTimeToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.ExtendedLifeTimeToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExtendedLifeTimeToken As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExtendedLifeTimeToken : bool" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.ExtendedLifeTimeToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erhalten Informationen für den Entwickler, ob während der normalen oder erweiterte Lebensdauer zurückgegebene Token ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdToken">
      <MemberSignature Language="C#" Value="public string IdToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.IdToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdToken As String" />
      <MemberSignature Language="F#" Value="member this.IdToken : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.IdToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die gesamte Id-Token ab, wenn vom Dienst oder Null zurückgegeben, wenn keine Id-Token zurückgegeben wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Bezeichner für den Mandanten, dem aus das Token abgerufen wurde. Diese Eigenschaft ist, null, wenn die Informationen des Mandanten nicht vom Dienst zurückgegeben wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserInfo">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo UserInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo UserInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.UserInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserInfo As UserInfo" />
      <MemberSignature Language="F#" Value="member this.UserInfo : Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.UserInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Benutzerinformationen, einschließlich Benutzer-ID ab Einige Elemente in UserInfo möglicherweise null, wenn nicht vom Dienst zurückgegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>