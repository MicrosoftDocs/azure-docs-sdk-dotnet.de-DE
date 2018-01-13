<Type Name="SharedKeyLiteAuthenticationHandler" FullName="Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyLiteAuthenticationHandler : Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyLiteAuthenticationHandler extends System.Object implements class Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyLiteAuthenticationHandler&#xA;Implements IAuthenticationHandler" />
  <TypeSignature Language="F#" Value="type SharedKeyLiteAuthenticationHandler = class&#xA;    interface IAuthenticationHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Use SharedKeyAuthenticationHandler")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt einen Handler, der die HTTP-Anforderungen mit einem gemeinsamen Schlüssel signiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedKeyLiteAuthenticationHandler (Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer canonicalizer, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials, string resourceAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer canonicalizer, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials, string resourceAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler.#ctor(Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (canonicalizer As ICanonicalizer, credentials As StorageCredentials, resourceAccountName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials * string -&gt; Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler" Usage="new Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler (canonicalizer, credentials, resourceAccountName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="canonicalizer" Type="Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
        <Parameter Name="resourceAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="canonicalizer">Eine Canonicalizer, die HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden konvertiert.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Objekt Anmeldeinformationen für die Anforderung anzugeben.</param>
        <param name="resourceAccountName">Der Name des Speicherkontos an, dem die HTTP-Anforderung zugreifen.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignRequest">
      <MemberSignature Language="C#" Value="public void SignRequest (System.Net.HttpWebRequest request, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SignRequest(class System.Net.HttpWebRequest request, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler.SignRequest(System.Net.HttpWebRequest,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="sharedKeyLiteAuthenticationHandler.SignRequest (request, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler.SignRequest(System.Net.HttpWebRequest,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="request">Die zum Signieren von HTTP-Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Signiert die angegebene HTTP-Anforderung mit einem gemeinsamen Schlüssel.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>