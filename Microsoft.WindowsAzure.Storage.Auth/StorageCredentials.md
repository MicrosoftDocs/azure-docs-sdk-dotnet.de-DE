<Type Name="StorageCredentials" FullName="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials">
  <TypeSignature Language="C#" Value="public sealed class StorageCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageCredentials" />
  <TypeSignature Language="F#" Value="type StorageCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Satz von Anmeldeinformationen zum Authentifizieren des Zugriffs auf ein Microsoft Azure Storage-Konto verwendet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string sasToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sasToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sasToken As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials sasToken" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sasToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasToken">Eine Zeichenfolge, die die SAS-Token darstellt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Klasse mit dem angegebenen freigegebenen SAS-Token.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, byte[] keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, unsigned int8[] keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * byte[] -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="accountName">Eine Zeichenfolge, die den Namen des Speicherkontos darstellt.</param>
        <param name="keyValue">Ein Array von Bytes, die den kontozugriffsschlüssel darstellen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Klasse mit dem angegebenen Kontonamen und Schlüsselwert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">Eine Zeichenfolge, die den Namen des Speicherkontos darstellt.</param>
        <param name="keyValue">Eine Zeichenfolge, die Base64-codierten kontozugriffsschlüssel darstellt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Klasse mit dem angegebenen Kontonamen und Schlüsselwert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, byte[] keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, unsigned int8[] keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As Byte(), keyName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * byte[] * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.Byte[]" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">Eine Zeichenfolge, die den Namen des Speicherkontos darstellt.</param>
        <param name="keyValue">Ein Array von Bytes, die den kontozugriffsschlüssel darstellen.</param>
        <param name="keyName">Eine Zeichenfolge, die den Namen des Schlüssels darstellt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> -Klasse mit dem angegebenen Kontonamen ein, die Schlüssel-Wert und den Schlüsselnamen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageCredentials (string accountName, string keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String, keyName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials : string * string * string -&gt; Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="new Microsoft.WindowsAzure.Storage.Auth.StorageCredentials (accountName, keyValue, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">Eine Zeichenfolge, die den Namen des Speicherkontos darstellt.</param>
        <param name="keyValue">Eine Zeichenfolge, die Base64-codierten kontozugriffsschlüssel darstellt.</param>
        <param name="keyName">Eine Zeichenfolge, die den Namen des Schlüssels darstellt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> -Klasse mit dem angegebenen Kontonamen ein, die Schlüssel-Wert und den Schlüsselnamen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den zugeordneten Kontonamen für die Anmeldeinformationen ab.
            </summary>
        <value>Der Kontoname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.WindowsAzure.Storage.Auth.StorageCredentials other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Equals(class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.Equals(Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As StorageCredentials) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; bool" Usage="storageCredentials.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="other">Die <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> zu diesem Objekt zu vergleichende Objekt.</param>
        <summary>
            Bestimmt, ob ein anderes <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Objekt gleich dieser Klassifizierung, indem Sie ihre SAS-Token, Kontonamen, Schlüsselnamen und Schlüsselwerte verglichen.
            </summary>
        <returns>
          <c>"true"</c> Wenn die beiden <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Objekte sind gleich sind, andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportBase64EncodedKey">
      <MemberSignature Language="C#" Value="public string ExportBase64EncodedKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ExportBase64EncodedKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.ExportBase64EncodedKey" />
      <MemberSignature Language="VB.NET" Value="Public Function ExportBase64EncodedKey () As String" />
      <MemberSignature Language="F#" Value="member this.ExportBase64EncodedKey : unit -&gt; string" Usage="storageCredentials.ExportBase64EncodedKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Exportiert den Wert des Zugriffsschlüssels in eine Base64-codierte Zeichenfolge.
            </summary>
        <returns>Der kontozugriffsschlüssel.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportKey">
      <MemberSignature Language="C#" Value="public byte[] ExportKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] ExportKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.ExportKey" />
      <MemberSignature Language="VB.NET" Value="Public Function ExportKey () As Byte()" />
      <MemberSignature Language="F#" Value="member this.ExportKey : unit -&gt; byte[]" Usage="storageCredentials.ExportKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt den kontoschlüssel für die Anmeldeinformationen an.
            </summary>
        <returns>Ein Array von Bytes, die den Schlüssel enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymous">
      <MemberSignature Language="C#" Value="public bool IsAnonymous { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymous" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsAnonymous" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAnonymous As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymous : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsAnonymous" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob die Anmeldeinformationen für den anonymen Zugriff sind.
            </summary>
        <value>
          <c>"true"</c> sind die Anmeldeinformationen für den anonymen Zugriff; andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSAS">
      <MemberSignature Language="C#" Value="public bool IsSAS { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSAS" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSAS" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSAS As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSAS : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSAS" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob die Anmeldeinformationen ein SAS-token ab.
            </summary>
        <value>
          <c>"true"</c> sind die Anmeldeinformationen eine shared Access Signature ist, andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSharedKey">
      <MemberSignature Language="C#" Value="public bool IsSharedKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSharedKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSharedKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSharedKey : bool" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.IsSharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob die Anmeldeinformationen ein gemeinsam verwendeter Schlüssel sind.
            </summary>
        <value>
          <c>"true"</c> sind die Anmeldeinformationen einem gemeinsam verwendeten Schlüssel ist, andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den zugeordneten Schlüsselnamen für die Anmeldeinformationen ab.
            </summary>
        <value>Der Schlüsselname.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASSignature">
      <MemberSignature Language="C#" Value="public string SASSignature { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SASSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASSignature" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SASSignature As String" />
      <MemberSignature Language="F#" Value="member this.SASSignature : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Wert der SAS-Token des <c>Sig</c> Parameter.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SASToken">
      <MemberSignature Language="C#" Value="public string SASToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SASToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SASToken As String" />
      <MemberSignature Language="F#" Value="member this.SASToken : string" Usage="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.SASToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das zugeordnete SAS-token für die Anmeldeinformationen ab.
            </summary>
        <value>Die SAS-Token.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransformUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri TransformUri (Microsoft.WindowsAzure.Storage.StorageUri resourceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.StorageUri TransformUri(class Microsoft.WindowsAzure.Storage.StorageUri resourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.TransformUri(Microsoft.WindowsAzure.Storage.StorageUri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TransformUri (resourceUri As StorageUri) As StorageUri" />
      <MemberSignature Language="F#" Value="member this.TransformUri : Microsoft.WindowsAzure.Storage.StorageUri -&gt; Microsoft.WindowsAzure.Storage.StorageUri" Usage="storageCredentials.TransformUri resourceUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
      </Parameters>
      <Docs>
        <param name="resourceUri">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt, das den Ressourcen-URI zu transformierende darstellt.</param>
        <summary>
            Transformiert einen Ressourcen-URI in einen SAS-URI durch Anfügen einer SAS-Token.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt, das die Signatur, einschließlich der Ressourcen-URI und das SAS-Token darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransformUri">
      <MemberSignature Language="C#" Value="public Uri TransformUri (Uri resourceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Uri TransformUri(class System.Uri resourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.TransformUri(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TransformUri (resourceUri As Uri) As Uri" />
      <MemberSignature Language="F#" Value="member this.TransformUri : Uri -&gt; Uri" Usage="storageCredentials.TransformUri resourceUri" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="resourceUri">Ein <see cref="T:System.Uri" /> Objekt, das den Ressourcen-URI zu transformierende darstellt.</param>
        <summary>
            Transformiert einen Ressourcen-URI in einen SAS-URI durch Anfügen einer SAS-Token.
            </summary>
        <returns>Ein <see cref="T:System.Uri" /> Objekt, das die Signatur, einschließlich der Ressourcen-URI und das SAS-Token darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (byte[] keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(unsigned int8[] keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As Byte())" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : byte[] -&gt; unit" Usage="storageCredentials.UpdateKey keyValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="keyValue">Der Schlüsselwert als Array von Bytes, die Sie aktualisieren.</param>
        <summary>
            Aktualisiert den Schlüsselwert für die Anmeldeinformationen an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : string -&gt; unit" Usage="storageCredentials.UpdateKey keyValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue">Der Schlüsselwert als Base64-codierte Zeichenfolge, zu aktualisieren.</param>
        <summary>
            Aktualisiert den Schlüsselwert für die Anmeldeinformationen an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (byte[] keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(unsigned int8[] keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As Byte(), keyName As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : byte[] * string -&gt; unit" Usage="storageCredentials.UpdateKey (keyValue, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.Byte[]" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue">Der Schlüsselwert als Array von Bytes, die Sie aktualisieren.</param>
        <param name="keyName">Der Schlüsselname zu aktualisieren.</param>
        <summary>
            Aktualisiert den Schlüsselwert und die Schlüsselnamen für die Anmeldeinformationen an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKey">
      <MemberSignature Language="C#" Value="public void UpdateKey (string keyValue, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateKey(string keyValue, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateKey(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateKey (keyValue As String, keyName As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateKey : string * string -&gt; unit" Usage="storageCredentials.UpdateKey (keyValue, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue">Der Schlüsselwert als Base64-codierte Zeichenfolge, zu aktualisieren.</param>
        <param name="keyName">Der Schlüsselname zu aktualisieren.</param>
        <summary>
            Aktualisiert den Schlüsselwert und die Schlüsselnamen für die Anmeldeinformationen an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSASToken">
      <MemberSignature Language="C#" Value="public void UpdateSASToken (string sasToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSASToken(string sasToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials.UpdateSASToken(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSASToken (sasToken As String)" />
      <MemberSignature Language="F#" Value="member this.UpdateSASToken : string -&gt; unit" Usage="storageCredentials.UpdateSASToken sasToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sasToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sasToken">Eine Zeichenfolge, die angibt, die SAS-token Wert, der aktualisiert.</param>
        <summary>
            Aktualisiert den gemeinsamen Zugriff Signature (SAS)-Tokenwert für mit einer SAS erstellten speicheranmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>