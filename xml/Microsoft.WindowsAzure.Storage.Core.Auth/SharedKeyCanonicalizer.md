<Type Name="SharedKeyCanonicalizer" FullName="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyCanonicalizer : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyCanonicalizer extends System.Object implements class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyCanonicalizer&#xA;Implements ICanonicalizer" />
  <TypeSignature Language="F#" Value="type SharedKeyCanonicalizer = class&#xA;    interface ICanonicalizer" />
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
      <InterfaceName>Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="02d30-101">Stellt eine Canonicalizer, die HTTP-Anforderungsdaten in ein Standardformat für das Signieren über das Shared Key-Authentifizierungsschema für den BLOB- oder Warteschlangendienst konvertiert.</span><span class="sxs-lookup"><span data-stu-id="02d30-101">Represents a canonicalizer that converts HTTP request data into a standard form appropriate for signing via the Shared Key authentication scheme for the Blob or Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationScheme">
      <MemberSignature Language="C#" Value="public string AuthorizationScheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.AuthorizationScheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationScheme As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationScheme : string" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.AuthorizationScheme" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.AuthorizationScheme</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="02d30-102">Ruft die für die Kanonikalisierung verwendete Authentifizierungsschema ab.</span><span class="sxs-lookup"><span data-stu-id="02d30-102">Gets the authorization scheme used for canonicalization.</span></span>
            </summary>
        <value><span data-ttu-id="02d30-103">Für die Kanonikalisierung verwendete Autorisierungsschemas.</span><span class="sxs-lookup"><span data-stu-id="02d30-103">The authorization scheme used for canonicalization.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeHttpRequest">
      <MemberSignature Language="C#" Value="public string CanonicalizeHttpRequest (System.Net.HttpWebRequest request, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CanonicalizeHttpRequest(class System.Net.HttpWebRequest request, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CanonicalizeHttpRequest (request As HttpWebRequest, accountName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string&#xA;override this.CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string" Usage="sharedKeyCanonicalizer.CanonicalizeHttpRequest (request, accountName)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="02d30-104">Die HTTP-Anforderung, die signiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="02d30-104">The HTTP request that needs to be signed.</span></span></param>
        <param name="accountName"><span data-ttu-id="02d30-105">Der Name des Speicherkontos an, dem die HTTP-Anforderung zugreifen.</span><span class="sxs-lookup"><span data-stu-id="02d30-105">The name of the storage account that the HTTP request will access.</span></span></param>
        <summary>
            <span data-ttu-id="02d30-106">Konvertiert die angegebene HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden an.</span><span class="sxs-lookup"><span data-stu-id="02d30-106">Converts the specified HTTP request data into a standard form appropriate for signing.</span></span>
            </summary>
        <returns><span data-ttu-id="02d30-107">Die kanonikalisierte Zeichenfolge, die die HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden enthält.</span><span class="sxs-lookup"><span data-stu-id="02d30-107">The canonicalized string containing the HTTP request data in a standard form appropriate for signing.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Instance">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer Instance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer Instance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.Instance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Instance As SharedKeyCanonicalizer" />
      <MemberSignature Language="F#" Value="member this.Instance : Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer.Instance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02d30-108">Ruft eine statische Instanz die <see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="02d30-108">Gets a static instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyCanonicalizer" /> object.</span></span>
            </summary>
        <value><span data-ttu-id="02d30-109">Die statische Instanz der Klasse.</span><span class="sxs-lookup"><span data-stu-id="02d30-109">The static instance of the class.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>