<Type Name="SftpLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService">
  <TypeSignature Language="C#" Value="public class SftpLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SftpLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class SftpLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type SftpLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("Sftp")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Einen verknüpften Dienst für einen SSH File Transfer Protocol (SFTP)-Server. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SftpLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SftpLinkedService (string host, string authenticationType, string username);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string host, string authenticationType, string username) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (host As String, authenticationType As String, username As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService : string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService (host, authenticationType, username)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="host" Type="System.String" />
        <Parameter Name="authenticationType" Type="System.String" />
        <Parameter Name="username" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="host">To be added.</param>
        <param name="authenticationType">To be added.</param>
        <param name="username">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService" /> Klasse mit erforderlichen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationType">
      <MemberSignature Language="C#" Value="public string AuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.AuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationType As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticationType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.AuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Der Authentifizierungstyp für die Verbindung mit dem SFTP-Server verwendet werden. Basic "oder" SshPublicKey muss. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptedCredential">
      <MemberSignature Language="C#" Value="public string EncryptedCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptedCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.EncryptedCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptedCredential As String" />
      <MemberSignature Language="F#" Value="member this.EncryptedCredential : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.EncryptedCredential" />
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
            Optional. Die verschlüsselten Anmeldeinformationen für Standardauthentifizierung oder SshPublicKey Authentifizierung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayName">
      <MemberSignature Language="C#" Value="public string GatewayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.GatewayName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.GatewayName" />
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
            Optional. Der Name des lokalen Netzwerkgateways.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Der Hostname der SFTP-Server.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostKeyFingerprint">
      <MemberSignature Language="C#" Value="public string HostKeyFingerprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostKeyFingerprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.HostKeyFingerprint" />
      <MemberSignature Language="VB.NET" Value="Public Property HostKeyFingerprint As String" />
      <MemberSignature Language="F#" Value="member this.HostKeyFingerprint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.HostKeyFingerprint" />
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
            Optional. Der Host-Taste Fingerabdruck des SFTP-Servers.
            Wenn SkipHostKeyValidation auf "false" festgelegt ist, sollte die HostKeyFingerprint angegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PassPhrase">
      <MemberSignature Language="C#" Value="public string PassPhrase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PassPhrase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PassPhrase" />
      <MemberSignature Language="VB.NET" Value="Public Property PassPhrase As String" />
      <MemberSignature Language="F#" Value="member this.PassPhrase : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PassPhrase" />
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
            Optional. Das Kennwort für die private SSH-Schlüssel zu entschlüsseln, wenn der private SSH-Schlüssel verschlüsselt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Password" />
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
            Optional. Kennwort zum Anmelden der SFTP-Server für die Standardauthentifizierung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Der TCP-Portnummer, die der SFTP-Server verwendet, um für Verbindungen mit Clients zu lauschen. Standardwert ist 22.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateKeyContent">
      <MemberSignature Language="C#" Value="public string PrivateKeyContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateKeyContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PrivateKeyContent" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateKeyContent As String" />
      <MemberSignature Language="F#" Value="member this.PrivateKeyContent : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PrivateKeyContent" />
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
            Optional. Base64-codierte SSH-private Key-Inhalte für die Authentifizierung SshPublicKey.
            Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden.
            Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateKeyPath">
      <MemberSignature Language="C#" Value="public string PrivateKeyPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateKeyPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PrivateKeyPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateKeyPath As String" />
      <MemberSignature Language="F#" Value="member this.PrivateKeyPath : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.PrivateKeyPath" />
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
            Optional. Der SSH-Privatschlüsseldatei Pfad für die SshPublicKey Authentifizierung. Nur gültig für die lokale Kopie.
            Für die lokale Kopie mit SshPublicKey Authentifizierung sollte PrivateKeyPath oder PrivateKeyContent angegeben werden.
            Der private SSH-Schlüssel sollte das Format „OpenSSH“ aufweisen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipHostKeyValidation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SkipHostKeyValidation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SkipHostKeyValidation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.SkipHostKeyValidation" />
      <MemberSignature Language="VB.NET" Value="Public Property SkipHostKeyValidation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SkipHostKeyValidation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.SkipHostKeyValidation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Bei "true", überspringen Sie die SSH-Host-Key-Überprüfung. Der Standardwert ist „false“.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.SftpLinkedService.Username" />
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
            Optional. Den Benutzernamen zur Anmeldung auf des SFTP-Servers. Es ist erforderlich, wenn EncryptedCredential null ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>