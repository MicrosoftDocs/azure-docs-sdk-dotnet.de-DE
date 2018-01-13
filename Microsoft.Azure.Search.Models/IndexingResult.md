<Type Name="IndexingResult" FullName="Microsoft.Azure.Search.Models.IndexingResult">
  <TypeSignature Language="C#" Value="public class IndexingResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexingResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexingResult" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexingResult" />
  <TypeSignature Language="F#" Value="type IndexingResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="77a53-101">Der Status eines Indizierungsvorgangs für ein einzelnes Dokument.</span><span class="sxs-lookup"><span data-stu-id="77a53-101">Status of an indexing operation for a single document.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="77a53-102">Initialisiert eine neue Instanz der IndexingResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="77a53-102">Initializes a new instance of the IndexingResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexingResult (string key = null, string errorMessage = null, bool succeeded = false, int statusCode = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string key, string errorMessage, bool succeeded, int32 statusCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexingResult.#ctor(System.String,System.String,System.Boolean,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional key As String = null, Optional errorMessage As String = null, Optional succeeded As Boolean = false, Optional statusCode As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexingResult : string * string * bool * int -&gt; Microsoft.Azure.Search.Models.IndexingResult" Usage="new Microsoft.Azure.Search.Models.IndexingResult (key, errorMessage, succeeded, statusCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="succeeded" Type="System.Boolean" />
        <Parameter Name="statusCode" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="77a53-103">Der Schlüssel eines Dokuments, das in die Indizierung Anforderung war.</span><span class="sxs-lookup"><span data-stu-id="77a53-103">The key of a document that was in the indexing request.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="77a53-104">Die Fehlermeldung, die erläutern, warum die Indizierung für das Dokument, das durch den Schlüssel identifizierte Vorgangsfehler; NULL, wenn die Indizierung war erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="77a53-104">The error message explaining why the indexing operation failed for the document identified by the key; null if indexing succeeded.</span></span></param>
        <param name="succeeded"><span data-ttu-id="77a53-105">Ein Wert, der angibt, ob der Indizierungsvorgang für das Dokument, das durch den Schlüssel identifizierte erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="77a53-105">A value indicating whether the indexing operation succeeded for the document identified by the key.</span></span></param>
        <param name="statusCode"><span data-ttu-id="77a53-106">Der Statuscode der der Indizierungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="77a53-106">The status code of the indexing operation.</span></span>
            <span data-ttu-id="77a53-107">Folgende Werte sind möglich: 200 für ein erfolgreiches update oder delete, 201 für erfolgreiche Erstellung, 400 für eine falsch formatierte Eingabedokument 404 für Dokument nicht gefunden, 409 für ein Versionskonflikt 422, wenn der Index vorübergehend nicht verfügbar ist oder 503 für die Ausführung des Diensts ist zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="77a53-107">Possible values include: 200 for a successful update or delete, 201 for successful document creation, 400 for a malformed input document, 404 for document not found, 409 for a version conflict, 422 when the index is temporarily unavailable, or 503 for when the service is too busy.</span></span></param>
        <summary>
            <span data-ttu-id="77a53-108">Initialisiert eine neue Instanz der IndexingResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="77a53-108">Initializes a new instance of the IndexingResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingResult.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string with get, set" Usage="Microsoft.Azure.Search.Models.IndexingResult.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77a53-109">Ruft die Fehlermeldung, die erläutern, warum der Indizierungsvorgang für das Dokument, das durch den Schlüssel identifizierte fehlgeschlagen ist. NULL, wenn die Indizierung war erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="77a53-109">Gets the error message explaining why the indexing operation failed for the document identified by the key; null if indexing succeeded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingResult.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Search.Models.IndexingResult.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77a53-110">Ruft den Schlüssel eines Dokuments, in dem die Volltextindizierung Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="77a53-110">Gets the key of a document that was in the indexing request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCode">
      <MemberSignature Language="C#" Value="public int StatusCode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingResult.StatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCode As Integer" />
      <MemberSignature Language="F#" Value="member this.StatusCode : int with get, set" Usage="Microsoft.Azure.Search.Models.IndexingResult.StatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77a53-111">Ruft den Statuscode der der Indizierungsvorgang ab.</span><span class="sxs-lookup"><span data-stu-id="77a53-111">Gets the status code of the indexing operation.</span></span> <span data-ttu-id="77a53-112">Folgende Werte sind möglich: 200 für ein erfolgreiches update oder delete, 201 für erfolgreiche Erstellung, 400 für eine falsch formatierte Eingabedokument 404 für Dokument nicht gefunden, 409 für ein Versionskonflikt 422, wenn der Index vorübergehend nicht verfügbar ist oder 503 für die Ausführung des Diensts ist zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="77a53-112">Possible values include: 200 for a successful update or delete, 201 for successful document creation, 400 for a malformed input document, 404 for document not found, 409 for a version conflict, 422 when the index is temporarily unavailable, or 503 for when the service is too busy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Succeeded">
      <MemberSignature Language="C#" Value="public bool Succeeded { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Succeeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexingResult.Succeeded" />
      <MemberSignature Language="VB.NET" Value="Public Property Succeeded As Boolean" />
      <MemberSignature Language="F#" Value="member this.Succeeded : bool with get, set" Usage="Microsoft.Azure.Search.Models.IndexingResult.Succeeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77a53-113">Ruft einen Wert, der angibt, ob der Indizierungsvorgang für das Dokument, das durch den Schlüssel identifizierte erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="77a53-113">Gets a value indicating whether the indexing operation succeeded for the document identified by the key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>