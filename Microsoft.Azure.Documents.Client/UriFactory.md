<Type Name="UriFactory" FullName="Microsoft.Azure.Documents.Client.UriFactory">
  <TypeSignature Language="C#" Value="public static class UriFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UriFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.UriFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class UriFactory" />
  <TypeSignature Language="F#" Value="type UriFactory = class" />
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
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="521d4-101">Hilfsklasse, die beim Erstellen der verschiedenen Uris unterstützen benötigt für die Verwendung mit der Instanz DocumentClient im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="521d4-101">Helper class to assist in creating the various Uris needed for use with the DocumentClient instance in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <example>
            <span data-ttu-id="521d4-102">Im folgenden Beispiel UriFactory verwendet, um eine DocumentCollectionLink zu erstellen und dann zum Erstellen eines Dokuments verwendet.</span><span class="sxs-lookup"><span data-stu-id="521d4-102">The example below uses UriFactory to create a DocumentCollectionLink and then uses that to create a Document.</span></span>
            <code language="c#"><![CDATA[ 
            Uri collUri = UriFactory.CreateDocumentCollectionUri("MyDb", "MyCollection");
            var doc = await client.CreateDocumentAsync(collUri, new {id = "MyDoc"});
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName="CreateAttachmentUri">
      <MemberSignature Language="C#" Value="public static Uri CreateAttachmentUri (string databaseId, string collectionId, string documentId, string attachmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateAttachmentUri(string databaseId, string collectionId, string documentId, string attachmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateAttachmentUri(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAttachmentUri (databaseId As String, collectionId As String, documentId As String, attachmentId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateAttachmentUri : string * string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateAttachmentUri (databaseId, collectionId, documentId, attachmentId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="documentId" Type="System.String" />
        <Parameter Name="attachmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-103">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-103">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-104">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-104">The collection id</span></span></param>
        <param name="documentId"><span data-ttu-id="521d4-105">Der Dokument-id</span><span class="sxs-lookup"><span data-stu-id="521d4-105">The document id</span></span></param>
        <param name="attachmentId"><span data-ttu-id="521d4-106">Die Attachment-id</span><span class="sxs-lookup"><span data-stu-id="521d4-106">The attachment id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-107">Erhält eine Datenbank, die Sammlung, die Dokument und die Anlage-Id, wird hierdurch einen Anlagenlink erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-107">Given a database, collection, document, and attachment id, this creates an attachment link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-108">Eine Anlagenlink im Format /dbs/ {0} / colls / \ {1\} / Dokumente / \ {2\} / Anlagen / \ {3\} mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" />, \ {2\} wird die <paramref name="documentId" /> und \ {3\} wird<paramref name="attachmentId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-108">An attachment link in the format of /dbs/{0}/colls/{1}/docs/{2}/attachments/{3} with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" />, {2} being the <paramref name="documentId" /> and {3} being <paramref name="attachmentId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-109">Wird verwendet werden, wenn beim Ersetzen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.Attachment" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-109">Would be used when replacing, or deleting an <see cref="T:Microsoft.Azure.Documents.Attachment" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateCollectionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateCollectionUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateCollectionUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateCollectionUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateCollectionUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateCollectionUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateCollectionUri (databaseId, collectionId)" />
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
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("CreateCollectionUri method is deprecated, please use CreateDocumentCollectionUri method instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-110">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-110">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-111">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-111">The collection id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-112">Wenn Sie eine Datenbank und Sammlung-Id, wird hierdurch einen Link der Auflistung erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-112">Given a database and collection id, this creates a collection link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-113">Eine Auflistung Link im Format /dbs/ {0} / colls / \ {1\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von den <paramref name="databaseId" /> und \ {1\}<paramref name="collectionId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-113">A collection link in the format of /dbs/{0}/colls/{1}/ with {0} being a Uri escaped version of the <paramref name="databaseId" /> and {1} being <paramref name="collectionId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-114">Verwendet werden würde, beim Aktualisieren oder Löschen einer <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, erstellen eine <see cref="T:Microsoft.Azure.Documents.Document" />, eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />, eine <see cref="T:Microsoft.Azure.Documents.Trigger" />, eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />, oder beim Ausführen einer Abfrage mit CreateDocumentQuery in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-114">Would be used when updating or deleting a <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, creating a <see cref="T:Microsoft.Azure.Documents.Document" />, a <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />, a <see cref="T:Microsoft.Azure.Documents.Trigger" />, a <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />, or when executing a query with CreateDocumentQuery in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateConflictUri">
      <MemberSignature Language="C#" Value="public static Uri CreateConflictUri (string databaseId, string collectionId, string conflictId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateConflictUri(string databaseId, string collectionId, string conflictId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateConflictUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateConflictUri (databaseId As String, collectionId As String, conflictId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateConflictUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateConflictUri (databaseId, collectionId, conflictId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="conflictId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-115">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-115">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-116">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-116">The collection id</span></span></param>
        <param name="conflictId"><span data-ttu-id="521d4-117">Die Id des Konflikt</span><span class="sxs-lookup"><span data-stu-id="521d4-117">The conflict id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-118">Wenn eine Datenbank, der Auflistung und der Konflikt-Id, wird hierdurch einen Konflikt Link erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-118">Given a database, collection and conflict id, this creates a conflict link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-119">Ein Konflikt Link im Format /dbs/ {0} / colls / \ {1\} / Konflikte / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="conflictId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-119">A conflict link in the format of /dbs/{0}/colls/{1}/conflicts/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="conflictId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-120">Wird beim Erstellen einer <see cref="T:Microsoft.Azure.Documents.Conflict" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-120">Would be used when creating a <see cref="T:Microsoft.Azure.Documents.Conflict" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDatabaseUri (string databaseId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDatabaseUri(string databaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDatabaseUri(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDatabaseUri (databaseId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDatabaseUri : string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDatabaseUri databaseId" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-121">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-121">The database id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-122">Wenn Sie eine Datenbank-Id, wird hierdurch einen datenbanklink erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-122">Given a database id, this creates a database link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-123">Ein datenbanklink in das Format der /dbs/ {0} / mit {0} wird von einem Uri mit Escapezeichen versehen Version der<paramref name="databaseId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-123">A database link in the format of /dbs/{0}/ with {0} being a Uri escaped version of the <paramref name="databaseId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-124">Wird verwendet werden, wenn das Erstellen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> oder ein <see cref="T:Microsoft.Azure.Documents.User" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-124">Would be used when creating or deleting a <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> or a <see cref="T:Microsoft.Azure.Documents.User" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDocumentCollectionUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDocumentCollectionUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentCollectionUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDocumentCollectionUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDocumentCollectionUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentCollectionUri (databaseId, collectionId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-125">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-125">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-126">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-126">The collection id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-127">Wenn Sie eine Datenbank und Sammlung-Id, wird hierdurch einen Link der Auflistung erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-127">Given a database and collection id, this creates a collection link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-128">Eine Auflistung Link im Format /dbs/ {0} / colls / \ {1\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von den <paramref name="databaseId" /> und \ {1\}<paramref name="collectionId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-128">A collection link in the format of /dbs/{0}/colls/{1}/ with {0} being a Uri escaped version of the <paramref name="databaseId" /> and {1} being <paramref name="collectionId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-129">Verwendet werden würde, beim Aktualisieren oder Löschen einer <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, erstellen eine <see cref="T:Microsoft.Azure.Documents.Document" />, eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />, eine <see cref="T:Microsoft.Azure.Documents.Trigger" />, eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />, oder beim Ausführen einer Abfrage mit CreateDocumentQuery in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-129">Would be used when updating or deleting a <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, creating a <see cref="T:Microsoft.Azure.Documents.Document" />, a <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />, a <see cref="T:Microsoft.Azure.Documents.Trigger" />, a <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />, or when executing a query with CreateDocumentQuery in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDocumentUri (string databaseId, string collectionId, string documentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDocumentUri(string databaseId, string collectionId, string documentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDocumentUri (databaseId As String, collectionId As String, documentId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDocumentUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentUri (databaseId, collectionId, documentId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="documentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-130">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-130">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-131">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-131">The collection id</span></span></param>
        <param name="documentId"><span data-ttu-id="521d4-132">Der Dokument-id</span><span class="sxs-lookup"><span data-stu-id="521d4-132">The document id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-133">Wenn eine Datenbank, die Sammlung und den Dokument-Id, wird hierdurch Link zu einem Dokument erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-133">Given a database, collection and document id, this creates a document link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-134">Link zu einem Dokument in das Format der /dbs/ {0} / colls / \ {1\} / Dokumente / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="documentId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-134">A document link in the format of /dbs/{0}/colls/{1}/docs/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="documentId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-135">Verwendet werden würde, beim Erstellen einer <see cref="T:Microsoft.Azure.Documents.Attachment" />, oder beim Ersetzen oder Löschen von einer <see cref="T:Microsoft.Azure.Documents.Document" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-135">Would be used when creating an <see cref="T:Microsoft.Azure.Documents.Attachment" />, or when replacing or deleting a <see cref="T:Microsoft.Azure.Documents.Document" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionKeyRangesUri">
      <MemberSignature Language="C#" Value="public static Uri CreatePartitionKeyRangesUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreatePartitionKeyRangesUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreatePartitionKeyRangesUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreatePartitionKeyRangesUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreatePartitionKeyRangesUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreatePartitionKeyRangesUri (databaseId, collectionId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-136">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-136">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-137">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-137">The collection id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-138">Eine Datenbank und die Sammlung erstellt, dies einen Partition Schlüsselbereichen Link im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="521d4-138">Given a database and collection, this creates a partition key ranges link in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-139">Partitionsschlüssel Bereiche Link im Format /dbs/ {0} / colls / \ {1\} / Pkranges mit {0} wird von einem Uri mit Escapezeichen versehen Version der <paramref name="databaseId" /> und \ {1\} wird <paramref name="collectionId" />.</span><span class="sxs-lookup"><span data-stu-id="521d4-139">A partition key ranges link in the format of /dbs/{0}/colls/{1}/pkranges with {0} being a Uri escaped version of the <paramref name="databaseId" /> and {1} being <paramref name="collectionId" />.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionUri">
      <MemberSignature Language="C#" Value="public static Uri CreatePermissionUri (string databaseId, string userId, string permissionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreatePermissionUri(string databaseId, string userId, string permissionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreatePermissionUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreatePermissionUri (databaseId As String, userId As String, permissionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreatePermissionUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreatePermissionUri (databaseId, userId, permissionId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="permissionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-140">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-140">The database id</span></span></param>
        <param name="userId"><span data-ttu-id="521d4-141">Die Benutzer-id</span><span class="sxs-lookup"><span data-stu-id="521d4-141">The user id</span></span></param>
        <param name="permissionId"><span data-ttu-id="521d4-142">Die Id der Berechtigung</span><span class="sxs-lookup"><span data-stu-id="521d4-142">The permission id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-143">Wenn Sie einen Datenbank und die Benutzer-Id, wird hierdurch eine Berechtigung Verknüpfung erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-143">Given a database and user id, this creates a permission link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-144">Eine Berechtigung Verknüpfung im Format /dbs/ {0} / Benutzer / \ {1\} / Berechtigungen / \ {2\} mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="userId" /> und \ {2\}<paramref name="permissionId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-144">A permission link in the format of /dbs/{0}/users/{1}/permissions/{2} with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="userId" /> and {2} being <paramref name="permissionId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-145">Würde verwendet werden, beim Ersetzen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.Permission" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-145">Would be used when replacing or deleting a <see cref="T:Microsoft.Azure.Documents.Permission" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureUri">
      <MemberSignature Language="C#" Value="public static Uri CreateStoredProcedureUri (string databaseId, string collectionId, string storedProcedureId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateStoredProcedureUri(string databaseId, string collectionId, string storedProcedureId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateStoredProcedureUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateStoredProcedureUri (databaseId As String, collectionId As String, storedProcedureId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateStoredProcedureUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateStoredProcedureUri (databaseId, collectionId, storedProcedureId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="storedProcedureId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-146">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-146">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-147">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-147">The collection id</span></span></param>
        <param name="storedProcedureId"><span data-ttu-id="521d4-148">Id der gespeicherten Prozedur</span><span class="sxs-lookup"><span data-stu-id="521d4-148">The stored procedure id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-149">Wenn eine Datenbank, die Sammlung und die gespeicherte Prozedur-Id, wird hierdurch einen gespeicherte Prozedur Link erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-149">Given a database, collection and stored proc id, this creates a stored proc link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-150">Eine gespeicherte Prozedur Link im Format /dbs/ {0} / colls / \ {1\} / Sprocs / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="storedProcedureId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-150">A stored procedure link in the format of /dbs/{0}/colls/{1}/sprocs/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="storedProcedureId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-151">Wird verwendet werden, wenn ersetzen, ausführen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-151">Would be used when replacing, executing, or deleting a <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerUri">
      <MemberSignature Language="C#" Value="public static Uri CreateTriggerUri (string databaseId, string collectionId, string triggerId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateTriggerUri(string databaseId, string collectionId, string triggerId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateTriggerUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateTriggerUri (databaseId As String, collectionId As String, triggerId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateTriggerUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateTriggerUri (databaseId, collectionId, triggerId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="triggerId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-152">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-152">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-153">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-153">The collection id</span></span></param>
        <param name="triggerId"><span data-ttu-id="521d4-154">Trigger-id</span><span class="sxs-lookup"><span data-stu-id="521d4-154">The trigger id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-155">Wenn eine Datenbank, die Sammlung und die Trigger-Id, wird hierdurch eine Verknüpfung Trigger erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-155">Given a database, collection and trigger id, this creates a trigger link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-156">Ein Trigger Link im Format /dbs/ {0} / colls / \ {1\} / Triggers / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="triggerId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-156">A trigger link in the format of /dbs/{0}/colls/{1}/triggers/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="triggerId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-157">Wird verwendet werden, wenn ersetzen, ausführen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.Trigger" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-157">Would be used when replacing, executing, or deleting a <see cref="T:Microsoft.Azure.Documents.Trigger" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateUserDefinedFunctionUri (string databaseId, string collectionId, string udfId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateUserDefinedFunctionUri(string databaseId, string collectionId, string udfId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateUserDefinedFunctionUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUserDefinedFunctionUri (databaseId As String, collectionId As String, udfId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateUserDefinedFunctionUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateUserDefinedFunctionUri (databaseId, collectionId, udfId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="udfId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-158">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-158">The database id</span></span></param>
        <param name="collectionId"><span data-ttu-id="521d4-159">Die Sammlungs-id</span><span class="sxs-lookup"><span data-stu-id="521d4-159">The collection id</span></span></param>
        <param name="udfId"><span data-ttu-id="521d4-160">Die Udf-id</span><span class="sxs-lookup"><span data-stu-id="521d4-160">The udf id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-161">Wenn eine Datenbank, die Sammlung und die Udf-Id, wird hierdurch einen Udf-Link erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-161">Given a database, collection and udf id, this creates a udf link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-162">Ein Udf-Link in das Format der /dbs/ {0} / colls / \ {1\} / UDF / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="udfId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-162">A udf link in the format of /dbs/{0}/colls/{1}/udfs/{2}/ with {0} being a Uri escaped version of the <paramref name="databaseId" />, {1} being <paramref name="collectionId" /> and {2} being the <paramref name="udfId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-163">Wird verwendet werden, wenn ersetzen, ausführen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-163">Would be used when replacing, executing, or deleting a <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateUserUri">
      <MemberSignature Language="C#" Value="public static Uri CreateUserUri (string databaseId, string userId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateUserUri(string databaseId, string userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateUserUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUserUri (databaseId As String, userId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateUserUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateUserUri (databaseId, userId)" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="userId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId"><span data-ttu-id="521d4-164">Die Datenbank-id</span><span class="sxs-lookup"><span data-stu-id="521d4-164">The database id</span></span></param>
        <param name="userId"><span data-ttu-id="521d4-165">Die Benutzer-id</span><span class="sxs-lookup"><span data-stu-id="521d4-165">The user id</span></span></param>
        <summary>
            <span data-ttu-id="521d4-166">Wenn Sie einen Datenbank und die Benutzer-Id, wird hierdurch einen benutzerlink erstellt.</span><span class="sxs-lookup"><span data-stu-id="521d4-166">Given a database and user id, this creates a user link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="521d4-167">Einen benutzerlink im Format /dbs/ {0} / Benutzer / \ {1\} / mit {0} wird eine Uri mit Escapezeichen versehen Version der <paramref name="databaseId" /> und \ {1\}<paramref name="userId" /></span><span class="sxs-lookup"><span data-stu-id="521d4-167">A user link in the format of /dbs/{0}/users/{1}/ with {0} being a Uri escaped version of the <paramref name="databaseId" /> and {1} being <paramref name="userId" /></span></span></returns>
        <remarks><span data-ttu-id="521d4-168">Würde verwendet werden, für die Erstellung einer <see cref="T:Microsoft.Azure.Documents.Permission" />, oder beim Ersetzen oder Löschen von einer <see cref="T:Microsoft.Azure.Documents.User" /> in Azure-Cosmos-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="521d4-168">Would be used when creating a <see cref="T:Microsoft.Azure.Documents.Permission" />, or when replacing or deleting a <see cref="T:Microsoft.Azure.Documents.User" /> in Azure Cosmos DB.</span></span></remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
  </Members>
</Type>