<Type Name="UserInfo" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo">
  <TypeSignature Language="C#" Value="public sealed class UserInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UserInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UserInfo" />
  <TypeSignature Language="F#" Value="type UserInfo = class" />
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
            Enthält Informationen eines einzelnen Benutzers. Diese Informationen werden für die Suche Tokencache verwendet. Auch wenn mit Benutzer-ID erstellt haben, wird Benutzer-ID an den Dienst gesendet, wenn Login_hint akzeptiert wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.#ctor" />
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
            Erstellen von Benutzerinformationen für Tokencache-Suche
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserInfo (Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.#ctor(Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As UserInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo : Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo" />
      </Parameters>
      <Docs>
        <param name="other">To be added.</param>
        <summary>
            Erstellen von Benutzerinformationen aus einem anderen UserInfo-Objekt kopiert
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayableId">
      <MemberSignature Language="C#" Value="public string DisplayableId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.DisplayableId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayableId As String" />
      <MemberSignature Language="F#" Value="member this.DisplayableId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.DisplayableId" />
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
            Ruft einen darstellbaren Wert im Format "userPrincipalName" (UPN). Der Wert kann leer sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FamilyName">
      <MemberSignature Language="C#" Value="public string FamilyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FamilyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.FamilyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FamilyName As String" />
      <MemberSignature Language="F#" Value="member this.FamilyName : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.FamilyName" />
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
            Ruft Familiennamen des Benutzers ab, wenn vom Dienst bereitgestellt. Wenn dies nicht der Fall ist, wird der Wert ist null. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GivenName">
      <MemberSignature Language="C#" Value="public string GivenName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GivenName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.GivenName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GivenName As String" />
      <MemberSignature Language="F#" Value="member this.GivenName : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.GivenName" />
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
            Ruft Vorname des Benutzers ab, wenn vom Dienst bereitgestellt. Wenn dies nicht der Fall ist, wird der Wert ist null. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdentityProvider">
      <MemberSignature Language="C#" Value="public string IdentityProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdentityProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.IdentityProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdentityProvider As String" />
      <MemberSignature Language="F#" Value="member this.IdentityProvider : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.IdentityProvider" />
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
            Ruft Identitätsanbieter ab, wenn vom Dienst zurückgegeben. Wenn dies nicht der Fall ist, wird der Wert ist null. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordChangeUrl">
      <MemberSignature Language="C#" Value="public Uri PasswordChangeUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri PasswordChangeUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.PasswordChangeUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PasswordChangeUrl As Uri" />
      <MemberSignature Language="F#" Value="member this.PasswordChangeUrl : Uri" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.PasswordChangeUrl" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Url ab, in denen der Benutzer ändern kann das ablaufende Kennwort. Der Wert kann leer sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordExpiresOn">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; PasswordExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; PasswordExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.PasswordExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PasswordExpiresOn As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.PasswordExpiresOn : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.PasswordExpiresOn" />
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
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Uhrzeit des Ablaufs des Kennworts ab. Standardwert ist 0.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueId">
      <MemberSignature Language="C#" Value="public string UniqueId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UniqueId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.UniqueId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UniqueId As String" />
      <MemberSignature Language="F#" Value="member this.UniqueId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.UniqueId" />
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
            Ruft die ID des Benutzers authentifiziert während tokenabruf ab. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>