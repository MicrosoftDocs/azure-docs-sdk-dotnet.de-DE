<Type Name="SharedKeyTableCanonicalizer" FullName="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyTableCanonicalizer : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyTableCanonicalizer extends System.Object implements class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyTableCanonicalizer&#xA;Implements ICanonicalizer" />
  <TypeSignature Language="F#" Value="type SharedKeyTableCanonicalizer = class&#xA;    interface ICanonicalizer" />
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
            <span data-ttu-id="72800-101">Stellt eine Canonicalizer, die HTTP-Anforderungsdaten in ein Standardformat für das Signieren über das Shared Key-Authentifizierungsschema für den Tabellendienst konvertiert.</span><span class="sxs-lookup"><span data-stu-id="72800-101">Represents a canonicalizer that converts HTTP request data into a standard form appropriate for signing via the Shared Key authentication scheme for the Table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationScheme">
      <MemberSignature Language="C#" Value="public string AuthorizationScheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer.AuthorizationScheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationScheme As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationScheme : string" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer.AuthorizationScheme" />
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
            <span data-ttu-id="72800-102">Ruft die für die Kanonikalisierung verwendete Authentifizierungsschema ab.</span><span class="sxs-lookup"><span data-stu-id="72800-102">Gets the authorization scheme used for canonicalization.</span></span>
            </summary>
        <value><span data-ttu-id="72800-103">Für die Kanonikalisierung verwendete Autorisierungsschemas.</span><span class="sxs-lookup"><span data-stu-id="72800-103">The authorization scheme used for canonicalization.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeHttpRequest">
      <MemberSignature Language="C#" Value="public string CanonicalizeHttpRequest (System.Net.HttpWebRequest request, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CanonicalizeHttpRequest(class System.Net.HttpWebRequest request, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CanonicalizeHttpRequest (request As HttpWebRequest, accountName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string&#xA;override this.CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string" Usage="sharedKeyTableCanonicalizer.CanonicalizeHttpRequest (request, accountName)" />
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
        <param name="request"><span data-ttu-id="72800-104">Die HTTP-Anforderung, die signiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="72800-104">The HTTP request that needs to be signed.</span></span></param>
        <param name="accountName"><span data-ttu-id="72800-105">Der Name des Speicherkontos an, dem die HTTP-Anforderung zugreifen.</span><span class="sxs-lookup"><span data-stu-id="72800-105">The name of the storage account that the HTTP request will access.</span></span></param>
        <summary>
            <span data-ttu-id="72800-106">Konvertiert die angegebene HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden an.</span><span class="sxs-lookup"><span data-stu-id="72800-106">Converts the specified HTTP request data into a standard form appropriate for signing.</span></span>
            </summary>
        <returns><span data-ttu-id="72800-107">Die kanonikalisierte Zeichenfolge, die die HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden enthält.</span><span class="sxs-lookup"><span data-stu-id="72800-107">The canonicalized string containing the HTTP request data in a standard form appropriate for signing.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Instance">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer Instance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer Instance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer.Instance" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Instance As SharedKeyTableCanonicalizer" />
      <MemberSignature Language="F#" Value="member this.Instance : Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer.Instance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72800-108">Ruft eine statische Instanz die <see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="72800-108">Gets a static instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Core.Auth.SharedKeyTableCanonicalizer" /> object.</span></span>
            </summary>
        <value><span data-ttu-id="72800-109">Die statische Instanz der Klasse.</span><span class="sxs-lookup"><span data-stu-id="72800-109">The static instance of the class.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>