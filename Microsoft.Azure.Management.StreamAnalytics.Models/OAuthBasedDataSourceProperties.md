<Type Name="OAuthBasedDataSourceProperties" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties">
  <TypeSignature Language="C#" Value="public class OAuthBasedDataSourceProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OAuthBasedDataSourceProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class OAuthBasedDataSourceProperties" />
  <TypeSignature Language="F#" Value="type OAuthBasedDataSourceProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Eigenschaften, die Datenquellen zugeordnet sind, die OAuth als ihre Authentifizierungsmodell verwenden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OAuthBasedDataSourceProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der OAuthBasedDataSourceProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OAuthBasedDataSourceProperties (string refreshToken = null, string tokenUserPrincipalName = null, string tokenUserDisplayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string refreshToken, string tokenUserPrincipalName, string tokenUserDisplayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional refreshToken As String = null, Optional tokenUserPrincipalName As String = null, Optional tokenUserDisplayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties : string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties (refreshToken, tokenUserPrincipalName, tokenUserDisplayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="refreshToken" Type="System.String" />
        <Parameter Name="tokenUserPrincipalName" Type="System.String" />
        <Parameter Name="tokenUserDisplayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="refreshToken">Ein Aktualisierungstoken, das verwendet werden kann, um eine gültige Zugriffstoken abrufen, die für die Authentifizierung bei der Datenquelle verwendet werden kann. Ein gültiges Aktualisierungstoken ist derzeit nur über das Azure Portal erhältlich. Es wird empfohlen, einen dummy-Zeichenfolgenwert für die Erstellung der Datenquelle und dann hörmal im Azure-Verwaltungsportal, um die Datenquelle zu authentifizieren, die diese Eigenschaft mit einem gültigen Aktualisierungstoken aktualisiert wird hier eingefügt werden soll. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="tokenUserPrincipalName">Prinzipalname (UPN) des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen. Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</param>
        <param name="tokenUserDisplayName">Der Anzeigename des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen. Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.</param>
        <summary>
            Initialisiert eine neue Instanz der OAuthBasedDataSourceProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="refreshToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Aktualisierungstoken, das verwendet werden kann, um eine gültige Zugriffstoken abrufen, die für die Authentifizierung bei der Datenquelle verwendet werden kann. Ein gültiges Aktualisierungstoken ist derzeit nur über das Azure Portal erhältlich. Es wird empfohlen, einen dummy-Zeichenfolgenwert für die Erstellung der Datenquelle und dann hörmal im Azure-Verwaltungsportal, um die Datenquelle zu authentifizieren, die diese Eigenschaft mit einem gültigen Aktualisierungstoken aktualisiert wird hier eingefügt werden soll. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserDisplayName">
      <MemberSignature Language="C#" Value="public string TokenUserDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserDisplayName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenUserDisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Benutzernamen für die Anzeige des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen. Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenUserPrincipalName">
      <MemberSignature Language="C#" Value="public string TokenUserPrincipalName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TokenUserPrincipalName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserPrincipalName" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenUserPrincipalName As String" />
      <MemberSignature Language="F#" Value="member this.TokenUserPrincipalName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.OAuthBasedDataSourceProperties.TokenUserPrincipalName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenUserPrincipalName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Benutzerprinzipalnamen (UPN) des Benutzers, der verwendet wurde, um das Aktualisierungstoken abzurufen. Verwenden Sie diese Eigenschaft, um Beachten Sie, welche Benutzer verwendet wurde, um das Aktualisierungstoken abzurufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>