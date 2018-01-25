<Type Name="Database" FullName="Microsoft.Azure.Documents.Database">
  <TypeSignature Language="C#" Value="public class Database : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Database extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Database" />
  <TypeSignature Language="VB.NET" Value="Public Class Database&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Database = class&#xA;    inherit Resource" />
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
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="aaac7-101">Stellt eine Datenbank im Azure-Cosmos-DB-Konto dar.</span><span class="sxs-lookup"><span data-stu-id="aaac7-101">Represents a database in the Azure Cosmos DB account.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="aaac7-102">Jedes Azure Cosmos-DB-Datenbank-Konto kann keine oder mehrere Datenbanken aufweisen.</span><span class="sxs-lookup"><span data-stu-id="aaac7-102">Each Azure Cosmos DB database account can have zero or more databases.</span></span> <span data-ttu-id="aaac7-103">Eine Datenbank in Azure-Cosmos-DB ist ein logischer Container für dokumentauflistungen und Benutzer.</span><span class="sxs-lookup"><span data-stu-id="aaac7-103">A database in Azure Cosmos DB is a logical container for document collections and users.</span></span>
            <span data-ttu-id="aaac7-104">Verweisen auf <see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#databases</see> für Weitere Informationen zu den Datenbanken.</span><span class="sxs-lookup"><span data-stu-id="aaac7-104">Refer to <see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#databases</see> for more details on databases.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
    <example>
            <span data-ttu-id="aaac7-105">Das folgende Beispiel erstellt eine neue Datenbank mit einer Id-Eigenschaft des "MyDatabase".</span><span class="sxs-lookup"><span data-stu-id="aaac7-105">The example below creates a new Database with an Id property of 'MyDatabase'.</span></span>
            <code language="c#"><![CDATA[ 
            using (DocumentClient client = new DocumentClient(new Uri("service endpoint"), "auth key"))
            {
                Database db = await client.CreateDatabaseAsync(new Database { Id = "MyDatabase" });
            }
            ]]></code></example>
    <example> 
            <span data-ttu-id="aaac7-106">Das folgende Beispiel erstellt eine Auflistung innerhalb dieser Datenbank mit OfferThroughput bis 10000 festgelegt.</span><span class="sxs-lookup"><span data-stu-id="aaac7-106">The example below creates a collection within this database with OfferThroughput set to 10000.</span></span>
            <code language="c#"><![CDATA[
            DocumentCollection coll = await client.CreateDocumentCollectionAsync(db.SelfLink,
                new DocumentCollection { Id = "MyCollection" }, 
                new RequestOptions { OfferThroughput = 10000} );
            ]]></code></example>
    <example>
            <span data-ttu-id="aaac7-107">Im Beispiel unten Abfragen für eine Datenbank-Id, die SelfLink abzurufen.</span><span class="sxs-lookup"><span data-stu-id="aaac7-107">The example below queries for a Database by Id to retrieve the SelfLink.</span></span>
            <code language="c#"><![CDATA[
            using Microsoft.Azure.Documents.Linq;
            Database database = client.CreateDatabaseQuery().Where(d => d.Id == "MyDatabase").AsEnumerable().FirstOrDefault();
            string databaseLink = database.SelfLink;
            ]]></code></example>
    <example>
            <span data-ttu-id="aaac7-108">Das folgende Beispiel löscht die Datenbank mithilfe der SelfLink-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="aaac7-108">The example below deletes the database using its SelfLink property.</span></span>
            <code language="c#"><![CDATA[
            await client.DeleteDatabaseAsync(db.SelfLink);
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Database ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Database.#ctor" />
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
            <span data-ttu-id="aaac7-109">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Database" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="aaac7-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Database" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionsLink">
      <MemberSignature Language="C#" Value="public string CollectionsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollectionsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Database.CollectionsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionsLink As String" />
      <MemberSignature Language="F#" Value="member this.CollectionsLink : string" Usage="Microsoft.Azure.Documents.Database.CollectionsLink" />
      <MemberType>Property</MemberType>
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_colls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aaac7-110">Ruft ab, der Self-link für Sammlungen aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="aaac7-110">Gets the self-link for collections from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="aaac7-111">Der Self-link für Sammlungen in der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="aaac7-111">The self-link for collections in the database.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="aaac7-112">Jede Azure Cosmos-DB-Ressource verfügt über eine statische, unveränderlich, adressierbaren URI.</span><span class="sxs-lookup"><span data-stu-id="aaac7-112">Every Azure Cosmos DB resource has a static, immutable, addressable URI.</span></span> <span data-ttu-id="aaac7-113">Bei Auflistungen hat dies das Format; / Dbs/Db_rid/colls /, wobei Db_rid den Wert des Ressourcen-Id der Datenbank darstellt. Eine Ressourcen-Id ist nicht die Id in einer Datenbank bei der Erstellung zugewiesen, aber eine intern erzeugte unveränderlichen Id auf.</span><span class="sxs-lookup"><span data-stu-id="aaac7-113">For collections, this takes the form of; /dbs/db_rid/colls/ where db_rid represents the value of the database's resource id. A resource id is not the id given to a database on creation, but an internally generated immutable id.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsersLink">
      <MemberSignature Language="C#" Value="public string UsersLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UsersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Database.UsersLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsersLink As String" />
      <MemberSignature Language="F#" Value="member this.UsersLink : string" Usage="Microsoft.Azure.Documents.Database.UsersLink" />
      <MemberType>Property</MemberType>
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_users")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="aaac7-114">Ruft ab, der Self-link für Benutzer aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="aaac7-114">Gets the self-link for users from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="aaac7-115">Der Self-link für Benutzer in der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="aaac7-115">The self-link for users in the database.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="aaac7-116">Jede Azure Cosmos-DB-Ressource verfügt über eine statische, unveränderlich, adressierbaren URI.</span><span class="sxs-lookup"><span data-stu-id="aaac7-116">Every Azure Cosmos DB resource has a static, immutable, addressable URI.</span></span> <span data-ttu-id="aaac7-117">Für Benutzer hat dies das Format; / Dbs/Db_rid/Benutzer /, wobei Db_rid den Wert des Ressourcen-Id der Datenbank darstellt. Eine Ressourcen-Id ist nicht die Id in einer Datenbank bei der Erstellung zugewiesen, aber eine intern erzeugte unveränderlichen Id auf.</span><span class="sxs-lookup"><span data-stu-id="aaac7-117">For users, this takes the form of; /dbs/db_rid/users/ where db_rid represents the value of the database's resource id. A resource id is not the id given to a database on creation, but an internally generated immutable id.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>