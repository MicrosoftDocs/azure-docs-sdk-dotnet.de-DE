<Type Name="SharedKeyAuthenticationHandler" FullName="Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyAuthenticationHandler : Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyAuthenticationHandler extends System.Object implements class Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyAuthenticationHandler&#xA;Implements IAuthenticationHandler" />
  <TypeSignature Language="F#" Value="type SharedKeyAuthenticationHandler = class&#xA;    interface IAuthenticationHandler" />
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
  <Docs>
    <summary>
            <span data-ttu-id="9ad60-101">Stellt einen Handler, der die HTTP-Anforderungen mit einem gemeinsamen Schlüssel signiert.</span><span class="sxs-lookup"><span data-stu-id="9ad60-101">Represents a handler that signs HTTP requests with a shared key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedKeyAuthenticationHandler (Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer canonicalizer, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials, string resourceAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer canonicalizer, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials, string resourceAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler.#ctor(Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (canonicalizer As ICanonicalizer, credentials As StorageCredentials, resourceAccountName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials * string -&gt; Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler" Usage="new Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler (canonicalizer, credentials, resourceAccountName)" />
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
        <param name="canonicalizer"><span data-ttu-id="9ad60-102">Eine Canonicalizer, die HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden konvertiert.</span><span class="sxs-lookup"><span data-stu-id="9ad60-102">A canonicalizer that converts HTTP request data into a standard form appropriate for signing.</span></span></param>
        <param name="credentials"><span data-ttu-id="9ad60-103">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> Objekt Anmeldeinformationen für die Anforderung anzugeben.</span><span class="sxs-lookup"><span data-stu-id="9ad60-103">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object providing credentials for the request.</span></span></param>
        <param name="resourceAccountName"><span data-ttu-id="9ad60-104">Der Name des Speicherkontos an, dem die HTTP-Anforderung zugreifen.</span><span class="sxs-lookup"><span data-stu-id="9ad60-104">The name of the storage account that the HTTP request will access.</span></span></param>
        <summary>
            <span data-ttu-id="9ad60-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9ad60-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignRequest">
      <MemberSignature Language="C#" Value="public void SignRequest (System.Net.HttpWebRequest request, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SignRequest(class System.Net.HttpWebRequest request, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyAuthenticationHandler.SignRequest(System.Net.HttpWebRequest,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="sharedKeyAuthenticationHandler.SignRequest (request, operationContext)" />
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
        <param name="request"><span data-ttu-id="9ad60-106">Die zum Signieren von HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9ad60-106">The HTTP request to sign.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9ad60-107">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9ad60-107">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9ad60-108">Signiert die angegebene HTTP-Anforderung mit einem gemeinsamen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="9ad60-108">Signs the specified HTTP request with a shared key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>