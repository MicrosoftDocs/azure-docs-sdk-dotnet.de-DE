<Type Name="SearchCredentials" FullName="Microsoft.Azure.Search.SearchCredentials">
  <TypeSignature Language="C#" Value="public class SearchCredentials : Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchCredentials extends Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.SearchCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchCredentials&#xA;Inherits ServiceClientCredentials" />
  <TypeSignature Language="F#" Value="type SearchCredentials = class&#xA;    inherit ServiceClientCredentials" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClientCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="816dd-101">Die Anmeldeinformationen zur Authentifizierung beim Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="816dd-101">Credentials used to authenticate to an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchCredentials (string apiKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string apiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchCredentials.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (apiKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.SearchCredentials : string -&gt; Microsoft.Azure.Search.SearchCredentials" Usage="new Microsoft.Azure.Search.SearchCredentials apiKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="apiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="apiKey"><span data-ttu-id="816dd-102">API-Schlüssel zur Authentifizierung beim Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="816dd-102">api-key used to authenticate to the Azure Search service.</span></span></param>
        <summary>
            <span data-ttu-id="816dd-103">Initialisiert eine neue Instanz der Klasse SearchCredentials mit einen Abfrageschlüssel oder ein Administratorschlüssel.</span><span class="sxs-lookup"><span data-stu-id="816dd-103">Initializes a new instance of the SearchCredentials class with a query key or an admin key.</span></span> <span data-ttu-id="816dd-104">Verwenden Sie einen Abfrageschlüssel aus, wenn Ihre Anwendung nicht über Schreibzugriff auf die Search-Dienst oder der Index erfordert.</span><span class="sxs-lookup"><span data-stu-id="816dd-104">Use a query key if your application does not require write access to the Search Service or index.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="816dd-105">Wenn Ihre Anwendung nur Abfragevorgänge für einen Index ausgeführt werden, sollten Sie übergeben einen Abfrageschlüssel für den <paramref name="apiKey" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="816dd-105">If your application performs only query operations on an index, we recommend passing a query key for the <paramref name="apiKey" /> parameter.</span></span> <span data-ttu-id="816dd-106">Dadurch wird sichergestellt, dass Sie nur-Lese-Zugriff auf den Index haben, der mit dem Prinzip der geringsten Rechte übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="816dd-106">This ensures that you have read-only access to the index, which is consistent with the principle of least privilege.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public string ApiKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.SearchCredentials.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiKey As String" />
      <MemberSignature Language="F#" Value="member this.ApiKey : string" Usage="Microsoft.Azure.Search.SearchCredentials.ApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="816dd-107">API-Schlüssel zur Authentifizierung beim Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="816dd-107">api-key used to authenticate to an Azure Search service.</span></span> <span data-ttu-id="816dd-108">Kann entweder einen Abfrageschlüssel für nur Abfragen oder ein Administratorschlüssel, der Verwaltung Index- und Dokument ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="816dd-108">Can be either a query key for querying only, or an admin key that enables index and document management as well.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessHttpRequestAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task ProcessHttpRequestAsync (System.Net.Http.HttpRequestMessage request, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task ProcessHttpRequestAsync(class System.Net.Http.HttpRequestMessage request, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SearchCredentials.ProcessHttpRequestAsync(System.Net.Http.HttpRequestMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ProcessHttpRequestAsync : System.Net.Http.HttpRequestMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="searchCredentials.ProcessHttpRequestAsync (request, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="816dd-109">HTTP-Anforderung</span><span class="sxs-lookup"><span data-stu-id="816dd-109">HTTP request</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="816dd-110">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="816dd-110">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="816dd-111">Die angegebene HTTP-Anforderung werden die Anmeldeinformationen hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="816dd-111">Adds the credentials to the given HTTP request.</span></span>
            </summary>
        <returns><span data-ttu-id="816dd-112">Eine Aufgabe, um den Fortschritt des asynchronen Vorgangs nachzuverfolgen.</span><span class="sxs-lookup"><span data-stu-id="816dd-112">A Task to track the progress of the async operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>