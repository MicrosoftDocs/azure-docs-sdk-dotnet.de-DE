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
            Stellt eine Datenbank im Azure-Cosmos-DB-Konto dar.
            </summary>
    <remarks>
            Jedes Azure Cosmos-DB-Datenbank-Konto kann keine oder mehrere Datenbanken aufweisen. Eine Datenbank in Azure-Cosmos-DB ist ein logischer Container für dokumentauflistungen und Benutzer.
            Verweisen auf <see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#databases</see> für Weitere Informationen zu den Datenbanken.
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
    <example>
            Das folgende Beispiel erstellt eine neue Datenbank mit einer Id-Eigenschaft des "MyDatabase".
            <code language="c#"><![CDATA[ 
            using (DocumentClient client = new DocumentClient(new Uri("service endpoint"), "auth key"))
            {
                Database db = await client.CreateDatabaseAsync(new Database { Id = "MyDatabase" });
            }
            ]]></code></example>
    <example> 
            Das folgende Beispiel erstellt eine Auflistung innerhalb dieser Datenbank mit OfferThroughput bis 10000 festgelegt.
            <code language="c#"><![CDATA[
            DocumentCollection coll = await client.CreateDocumentCollectionAsync(db.SelfLink,
                new DocumentCollection { Id = "MyCollection" }, 
                new RequestOptions { OfferThroughput = 10000} );
            ]]></code></example>
    <example>
            Im Beispiel unten Abfragen für eine Datenbank-Id, die SelfLink abzurufen.
            <code language="c#"><![CDATA[
            using Microsoft.Azure.Documents.Linq;
            Database database = client.CreateDatabaseQuery().Where(d => d.Id == "MyDatabase").AsEnumerable().FirstOrDefault();
            string databaseLink = database.SelfLink;
            ]]></code></example>
    <example>
            Das folgende Beispiel löscht die Datenbank mithilfe der SelfLink-Eigenschaft.
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
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Database" /> Klasse für den Azure-Cosmos-DB-Dienst.
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
            Ruft ab, der Self-link für Sammlungen aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Self-link für Sammlungen in der Datenbank.
            </value>
        <remarks>
            Jede Azure Cosmos-DB-Ressource verfügt über eine statische, unveränderlich, adressierbaren URI. Bei Auflistungen hat dies das Format; / Dbs/Db_rid/colls /, wobei Db_rid den Wert des Ressourcen-Id der Datenbank darstellt. Eine Ressourcen-Id ist nicht die Id in einer Datenbank bei der Erstellung zugewiesen, aber eine intern erzeugte unveränderlichen Id auf.
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
            Ruft ab, der Self-link für Benutzer aus dem Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Self-link für Benutzer in der Datenbank.
            </value>
        <remarks>
            Jede Azure Cosmos-DB-Ressource verfügt über eine statische, unveränderlich, adressierbaren URI. Für Benutzer hat dies das Format; / Dbs/Db_rid/Benutzer /, wobei Db_rid den Wert des Ressourcen-Id der Datenbank darstellt. Eine Ressourcen-Id ist nicht die Id in einer Datenbank bei der Erstellung zugewiesen, aber eine intern erzeugte unveränderlichen Id auf.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>