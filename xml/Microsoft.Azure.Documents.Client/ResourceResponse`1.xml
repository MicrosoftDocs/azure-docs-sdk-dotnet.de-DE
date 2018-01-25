<Type Name="ResourceResponse&lt;TResource&gt;" FullName="Microsoft.Azure.Documents.Client.ResourceResponse&lt;TResource&gt;">
  <TypeSignature Language="C#" Value="public class ResourceResponse&lt;TResource&gt; : Microsoft.Azure.Documents.Client.ResourceResponseBase, Microsoft.Azure.Documents.Client.IResourceResponse&lt;TResource&gt; where TResource : Resourcenew()" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceResponse`1&lt;.ctor (class Microsoft.Azure.Documents.Resource) TResource&gt; extends Microsoft.Azure.Documents.Client.ResourceResponseBase implements class Microsoft.Azure.Documents.Client.IResourceResponse`1&lt;!TResource&gt;, class Microsoft.Azure.Documents.Client.IResourceResponseBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceResponse(Of TResource)&#xA;Inherits ResourceResponseBase&#xA;Implements IResourceResponse(Of TResource)" />
  <TypeSignature Language="F#" Value="type ResourceResponse&lt;'Resource (requires 'Resource :&gt; Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; = class&#xA;    inherit ResourceResponseBase&#xA;    interface IResourceResponse&lt;'Resource (requires 'Resource :&gt; Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;&#xA;    interface IResourceResponseBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TResource">
      <Constraints>
        <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
        <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Client.ResourceResponseBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IResourceResponse&lt;TResource&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TResource"><span data-ttu-id="441b4-101">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="441b4-101">the resource type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="441b4-102">Stellt die Vorlagenklasse, die von Methoden, die einzelnen Objekte zurückgeben, in der Azure-Cosmos-DB-Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="441b4-102">Represents the template class used by methods returning single objects in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="441b4-103">Alle Antworten aus erstellt, gelesen, aktualisiert und löscht Azure Cosmos-DB Ressourcen return die Antwort in einem ResourceResponse-Objekt umschlossen.</span><span class="sxs-lookup"><span data-stu-id="441b4-103">All responses from creates, reads, updates and deletes of Azure Cosmos DB resources return the response wrapped in a ResourceResponse object.</span></span> <span data-ttu-id="441b4-104">Die Metadaten aus der Antwort-Header aus dem Azure-Cosmos-DB-Aufruf, einschließlich der anforderungseinheiten (RequestCharge), Aktivitäts-ID und Kontingente/Nutzung der Ressourcen enthält.</span><span class="sxs-lookup"><span data-stu-id="441b4-104">This contains the metadata from the response headers from the Azure Cosmos DB call including the request units (RequestCharge), activity ID and quotas/usage of resources.</span></span>
            </remarks>
    <altmember cref="P:Microsoft.Azure.Documents.Client.ResourceResponse`1.Resource" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.FeedResponse`1" />
    <example>
            <span data-ttu-id="441b4-105">Das folgende Beispiel extrahiert anforderungseinheiten genutzt wird, Aktivitäts-ID und den StatusCode von einem CreateDocumentAsync-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="441b4-105">The following example extracts the request units consumed, activity ID and StatusCode from a CreateDocumentAsync call.</span></span>
            <code language="c#"><![CDATA[
            ResourceResponse<Document> response = await client.CreateDocumentAsync(collectionLink, document);
            Console.WriteLine(response.RequestCharge);
            Console.WriteLine(response.ActivityId); 
            Console.WriteLine(response.StatusCode); // HttpStatusCode.Created or 201
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.ResourceResponse`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="441b4-106">Konstruktor zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="441b4-106">Constructor exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceResponse (TResource resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!TResource resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.ResourceResponse`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (resource As TResource)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; : 'Resource -&gt; Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;" Usage="new Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; resource" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resource" Type="TResource" />
      </Parameters>
      <Docs>
        <param name="resource"></param>
        <summary>
            <span data-ttu-id="441b4-107">Konstruktor zum Simulieren von Zwecken für den Azure-Cosmos-DB-Dienst zugänglich gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="441b4-107">Constructor exposed for mocking purposes for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator TResource (Microsoft.Azure.Documents.Client.ResourceResponse&lt;TResource&gt; source);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname !TResource op_Implicit(class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;!TResource&gt; source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.ResourceResponse`1.op_Implicit(Microsoft.Azure.Documents.Client.ResourceResponse{`0})~`0" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (source As ResourceResponse(Of TResource)) As TResource" />
      <MemberSignature Language="F#" Value="static member op_Implicit : Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt; -&gt; 'Resource" Usage="Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;.op_Implicit source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Documents.Client.ResourceResponse&lt;TResource&gt;" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="441b4-108">Die Quelle ResourceResponse.</span><span class="sxs-lookup"><span data-stu-id="441b4-108">The ResourceResponse source.</span></span></param>
        <summary>
            <span data-ttu-id="441b4-109">Gibt die Ressource in der Antwort implizit aus dem Azure-Cosmos-DB-Dienst zurück.</span><span class="sxs-lookup"><span data-stu-id="441b4-109">Returns the resource in the response implicitly from the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="441b4-110">Die Ressourcenobjekt.</span><span class="sxs-lookup"><span data-stu-id="441b4-110">The resource object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public TResource Resource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TResource Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.ResourceResponse`1.Resource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resource As TResource" />
      <MemberSignature Language="F#" Value="member this.Resource : 'Resource" Usage="Microsoft.Azure.Documents.Client.ResourceResponse&lt;'Resource (requires 'Resource :&gt; Microsoft.Azure.Documents.Resource and 'Resource : (new : unit -&gt; 'Resource))&gt;.Resource" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Documents.Client.IResourceResponse`1.Resource</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="441b4-111">Ruft die Ressource, die in der Antwort vom Dienst Azure-Cosmos-Datenbank zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="441b4-111">Gets the resource returned in the response from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="441b4-112">Die Ressource, die in der Antwort zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="441b4-112">The resource returned in the response.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>