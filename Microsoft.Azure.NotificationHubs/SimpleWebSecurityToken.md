<Type Name="SimpleWebSecurityToken" FullName="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken">
  <TypeSignature Language="C#" Value="public class SimpleWebSecurityToken : System.IdentityModel.Tokens.SecurityToken" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SimpleWebSecurityToken extends System.IdentityModel.Tokens.SecurityToken" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" />
  <TypeSignature Language="VB.NET" Value="Public Class SimpleWebSecurityToken&#xA;Inherits SecurityToken" />
  <TypeSignature Language="F#" Value="type SimpleWebSecurityToken = class&#xA;    inherit SecurityToken" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IdentityModel.Tokens.SecurityToken</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Ein Sicherheitstoken, die ein einfaches Webtoken umschließt.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken : string -&gt; Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" Usage="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken tokenString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString">Eine Zeichenfolge, die das Simple Web Token darstellt.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" /> Klasse mit dem angegebenen Simple Web Token.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString, DateTime expiry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.#ctor(System.String,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken : string * DateTime -&gt; Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" Usage="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken (tokenString, expiry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="tokenString">Eine Zeichenfolge, die das Simple Web Token darstellt.</param>
        <param name="expiry">Das Ablaufdatum des simple Web Tokens.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" /> Klasse mit dem angegebenen Datum für Simple Web Token und die ablauftoleranz.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NullReferenceException">tokenString</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string id, string tokenString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string tokenString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, tokenString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken : string * string -&gt; Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" Usage="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken (id, tokenString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tokenString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ein eindeutiger Bezeichner für das Simple Web Token.</param>
        <param name="tokenString">Eine Zeichenfolge, die das Simple Web Token darstellt.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" /> -Klasse mit dem angegebenen token-ID und Simple Web Token.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NullReferenceException">Die <paramref name="id" /> Parameter oder <paramref name="tokenString" /> -Parameter ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SimpleWebSecurityToken (string tokenString, DateTime expiry, string audience);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tokenString, valuetype System.DateTime expiry, string audience) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.#ctor(System.String,System.DateTime,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tokenString As String, expiry As DateTime, audience As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken : string * DateTime * string -&gt; Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" Usage="new Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken (tokenString, expiry, audience)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tokenString" Type="System.String" />
        <Parameter Name="expiry" Type="System.DateTime" />
        <Parameter Name="audience" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tokenString">Eine Zeichenfolge, die das Simple Web Token darstellt.</param>
        <param name="expiry">Das Ablaufdatum des simple Web Tokens.</param>
        <param name="audience">Die Zielgruppe für das einfache webtoken.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken" />-Klasse.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NullReferenceException">
            TokenString oder Zielgruppe
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Audience">
      <MemberSignature Language="C#" Value="public string Audience { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Audience" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.Audience" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Audience As String" />
      <MemberSignature Language="F#" Value="member this.Audience : string" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.Audience" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Zielgruppe für das simple webtoken ab.</summary>
        <value>Die Zielgruppe für das einfache webtoken.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AudienceFieldName">
      <MemberSignature Language="C#" Value="protected virtual string AudienceFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AudienceFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.AudienceFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property AudienceFieldName As String" />
      <MemberSignature Language="F#" Value="member this.AudienceFieldName : string" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.AudienceFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Zielgruppe Feldnamen ab.</summary>
        <value>Der Feldname der Zielgruppe.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOn">
      <MemberSignature Language="C#" Value="public DateTime ExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.ExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresOn As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresOn : DateTime" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.ExpiresOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Datum und Uhrzeit, die das Sicherheitstoken abläuft.</summary>
        <value>Das Datum und Uhrzeit, die das Sicherheitstoken abläuft.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOnFieldName">
      <MemberSignature Language="C#" Value="protected virtual string ExpiresOnFieldName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpiresOnFieldName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.ExpiresOnFieldName" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property ExpiresOnFieldName As String" />
      <MemberSignature Language="F#" Value="member this.ExpiresOnFieldName : string" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.ExpiresOnFieldName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Feldnamen der tokenablauf zugeordnet.</summary>
        <value>Der Feldname der tokenablauf zugeordnet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public override string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die ID der Simple Web Token zugeordnet.</summary>
        <value>Die ID der Simple Web Token zugeordnet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueSeparator">
      <MemberSignature Language="C#" Value="protected virtual string KeyValueSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyValueSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.KeyValueSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property KeyValueSeparator As String" />
      <MemberSignature Language="F#" Value="member this.KeyValueSeparator : string" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.KeyValueSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Schlüssel-Wert-Trennzeichen, die dem Token zugeordnet.</summary>
        <value>Das Schlüssel-Wert-Trennzeichen, das dem Token zugeordnet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairSeparator">
      <MemberSignature Language="C#" Value="protected virtual string PairSeparator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PairSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.PairSeparator" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable ReadOnly Property PairSeparator As String" />
      <MemberSignature Language="F#" Value="member this.PairSeparator : string" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.PairSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Paar Trennzeichen, die dem Token zugeordnet.</summary>
        <value>Das Paar-Trennzeichen, das dem Token zugeordnet ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityKeys">
      <MemberSignature Language="C#" Value="public override System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt; SecurityKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.IdentityModel.Tokens.SecurityKey&gt; SecurityKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.SecurityKeys" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property SecurityKeys As ReadOnlyCollection(Of SecurityKey)" />
      <MemberSignature Language="F#" Value="member this.SecurityKeys : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt;" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.SecurityKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.IdentityModel.Tokens.SecurityKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die dem Sicherheitstoken zugeordneten kryptografischen Schlüssel ab.</summary>
        <value>Ein <see cref="T:System.Collections.ObjectModel.ReadOnlyCollection`1" /> des Typs <see cref="T:System.IdentityModel.Tokens.SecurityKey" /> , die den Satz von Simple Web Token zugeordneten Schlüssel enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.Token" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.Token" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Simple Web Token ab.</summary>
        <value>Das einfache Webtoken.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidFrom">
      <MemberSignature Language="C#" Value="public override DateTime ValidFrom { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ValidFrom" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.ValidFrom" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property ValidFrom As DateTime" />
      <MemberSignature Language="F#" Value="member this.ValidFrom : DateTime" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.ValidFrom" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Noch nicht implementiert. </summary>
        <value>Löst eine <see cref="T:System.NotImplementedException" /> aus.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidTo">
      <MemberSignature Language="C#" Value="public override DateTime ValidTo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ValidTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.ValidTo" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property ValidTo As DateTime" />
      <MemberSignature Language="F#" Value="member this.ValidTo : DateTime" Usage="Microsoft.Azure.NotificationHubs.SimpleWebSecurityToken.ValidTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Noch nicht implementiert.</summary>
        <value>Löst eine <see cref="T:System.NotImplementedException" /> aus.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>