<Type Name="ICanonicalizer" FullName="Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer">
  <TypeSignature Language="C#" Value="public interface ICanonicalizer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICanonicalizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICanonicalizer" />
  <TypeSignature Language="F#" Value="type ICanonicalizer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="854c6-101">Stellt eine Canonicalizer, die HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden konvertiert.</span><span class="sxs-lookup"><span data-stu-id="854c6-101">Represents a canonicalizer that converts HTTP request data into a standard form appropriate for signing.</span></span></para>
      <para><span data-ttu-id="854c6-102">Ausführliche Informationen zum Authentifizieren einer Anforderung finden Sie unter <see href="http://msdn.microsoft.com/en-us/library/windowsazure/dd179428.aspx">Authentifizierung für Microsoft Azure-Speicherdienste</see>.</span><span class="sxs-lookup"><span data-stu-id="854c6-102">For detailed information on how to authenticate a request, see <see href="http://msdn.microsoft.com/en-us/library/windowsazure/dd179428.aspx">Authentication for the Microsoft Azure Storage Services</see>.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthorizationScheme">
      <MemberSignature Language="C#" Value="public string AuthorizationScheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthorizationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.AuthorizationScheme" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthorizationScheme As String" />
      <MemberSignature Language="F#" Value="member this.AuthorizationScheme : string" Usage="Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.AuthorizationScheme" />
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
            <span data-ttu-id="854c6-103">Ruft die für die Kanonikalisierung verwendete Authentifizierungsschema ab.</span><span class="sxs-lookup"><span data-stu-id="854c6-103">Gets the authorization scheme used for canonicalization.</span></span>
            </summary>
        <value><span data-ttu-id="854c6-104">Für die Kanonikalisierung verwendete Autorisierungsschemas.</span><span class="sxs-lookup"><span data-stu-id="854c6-104">The authorization scheme used for canonicalization.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanonicalizeHttpRequest">
      <MemberSignature Language="C#" Value="public string CanonicalizeHttpRequest (System.Net.HttpWebRequest request, string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CanonicalizeHttpRequest(class System.Net.HttpWebRequest request, string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer.CanonicalizeHttpRequest(System.Net.HttpWebRequest,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CanonicalizeHttpRequest (request As HttpWebRequest, accountName As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CanonicalizeHttpRequest : System.Net.HttpWebRequest * string -&gt; string" Usage="iCanonicalizer.CanonicalizeHttpRequest (request, accountName)" />
      <MemberType>Method</MemberType>
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
        <param name="request"><span data-ttu-id="854c6-105">Die HTTP-Anforderung, die signiert werden muss.</span><span class="sxs-lookup"><span data-stu-id="854c6-105">The HTTP request that needs to be signed.</span></span></param>
        <param name="accountName"><span data-ttu-id="854c6-106">Der Name des Speicherkontos an, dem die HTTP-Anforderung zugreifen.</span><span class="sxs-lookup"><span data-stu-id="854c6-106">The name of the storage account that the HTTP request will access.</span></span></param>
        <summary>
            <span data-ttu-id="854c6-107">Konvertiert die angegebene HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden an.</span><span class="sxs-lookup"><span data-stu-id="854c6-107">Converts the specified HTTP request data into a standard form appropriate for signing.</span></span>
            </summary>
        <returns><span data-ttu-id="854c6-108">Die kanonikalisierte Zeichenfolge, die die HTTP-Anforderungsdaten in ein Standardformat zum Signieren von entsprechenden enthält.</span><span class="sxs-lookup"><span data-stu-id="854c6-108">The canonicalized string containing the HTTP request data in a standard form appropriate for signing.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>