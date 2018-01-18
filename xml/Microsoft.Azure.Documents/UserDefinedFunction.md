<Type Name="UserDefinedFunction" FullName="Microsoft.Azure.Documents.UserDefinedFunction">
  <TypeSignature Language="C#" Value="public class UserDefinedFunction : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserDefinedFunction extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.UserDefinedFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class UserDefinedFunction&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type UserDefinedFunction = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="a1747-101">Stellt einen benutzerdefinierten benutzerdefinierten Funktion in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a1747-101">Represents a user defined function in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="a1747-102">Azure Cosmos-Datenbank unterstützt JavaScript benutzerdefinierte Funktionen (UDFs), die in der Datenbank gespeichert und können in Abfragen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="a1747-102">Azure Cosmos DB supports JavaScript user defined functions (UDFs) which are stored in the database and can be used inside queries.</span></span> <span data-ttu-id="a1747-103">Verweisen Sie auf http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration für die Verwendung von benutzerdefinierten Funktionen in Abfragen.</span><span class="sxs-lookup"><span data-stu-id="a1747-103">Refer to http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration for how to use UDFs within queries.</span></span>
            <span data-ttu-id="a1747-104">Http://azure.microsoft.com/documentation/articles/documentdb-programming/#udf für weitere Details zum Implementieren von benutzerdefinierten Funktionen in JavaScript finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="a1747-104">Refer to http://azure.microsoft.com/documentation/articles/documentdb-programming/#udf for more details about implementing UDFs in JavaScript.</span></span>
            </remarks>
    <example>
            <span data-ttu-id="a1747-105">Die folgenden Beispiele zeigen, wie zum Registrieren und Verwenden von benutzerdefinierten Funktionen.</span><span class="sxs-lookup"><span data-stu-id="a1747-105">The following examples show how to register and use UDFs.</span></span>
            <code language="c#"><![CDATA[
            await client.CreateUserDefinedFunctionAsync(collectionLink, new UserDefinedFunction { Id = "calculateTax", Body = @"function(amt) { return amt * 0.05; }" });
            client.CreateDocumentQuery<Book>(collectionLink, "SELECT VALUE udf.calculateTax(b.price) FROM books b");
            client.CreateDocumentQuery<Book>(collectionLink, new SqlQuerySpec("SELECT VALUE udf.calculateTax(b.price) FROM books b"));
            client.CreateDocumentQuery<Book>(collectionLink).Select(b => UserDefinedFunctionProvider.Invoke("calculateTax", b.Price));
            
            await client.CreateUserDefinedFunctionAsync(collectionLink, new UserDefinedFunction { Id = "toLowerCase", Body = @"function(s) { return s.ToLowerCase(); }" });
            client.CreateDocumentQuery<Book>(collectionLink, "SELECT * FROM books b WHERE b.toLowerCase = 'war and peace'");
            client.CreateDocumentQuery<Book>(collectionLink, new SqlQuerySpec(
                "SELECT * FROM books b WHERE b.toLowerCase = @bookNameLowerCase",
                new SqlParameterCollection(new SqlParameter[] {new SqlParameter { Name = "@bookNameLowerCase", Value = "War And Peace".ToLower()
             }})));
             client.CreateDocumentQuery<Book>(collectionLink).Where(b => UserDefinedFunctionProvider.Invoke("toLowerCase", b.Title) == "war and peace");
             ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserDefinedFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.UserDefinedFunction.#ctor" />
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
            <span data-ttu-id="a1747-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a1747-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.UserDefinedFunction.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.Documents.UserDefinedFunction.Body" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1747-107">Ruft ab oder legt den Text der benutzerdefinierten Funktion für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a1747-107">Gets or sets the body of the user defined function for the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="a1747-108">Der Text des Benutzers benutzerdefinierten Funktion.</span><span class="sxs-lookup"><span data-stu-id="a1747-108">The body of the user defined function.</span></span></value>
        <remarks><span data-ttu-id="a1747-109">Dies muss eine gültige JavaScript-Funktion z. B. "Function (Eingabe) {return input.toLowerCase();}" sein.</span><span class="sxs-lookup"><span data-stu-id="a1747-109">This must be a valid JavaScript function e.g. "function (input) { return input.toLowerCase(); }".</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>