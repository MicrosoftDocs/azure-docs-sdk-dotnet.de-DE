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
            Stellt einen benutzerdefinierten benutzerdefinierten Funktion in der Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>
            Azure Cosmos-Datenbank unterstützt JavaScript benutzerdefinierte Funktionen (UDFs), die in der Datenbank gespeichert und können in Abfragen verwendet werden. Verweisen Sie auf http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration für die Verwendung von benutzerdefinierten Funktionen in Abfragen.
            Http://azure.microsoft.com/documentation/articles/documentdb-programming/#udf für weitere Details zum Implementieren von benutzerdefinierten Funktionen in JavaScript finden Sie unter.
            </remarks>
    <example>
            Die folgenden Beispiele zeigen, wie zum Registrieren und Verwenden von benutzerdefinierten Funktionen.
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
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Klasse für den Azure-Cosmos-DB-Dienst.
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
            Ruft ab oder legt den Text der benutzerdefinierten Funktion für den Azure-Cosmos-DB-Dienst.
            </summary>
        <value>Der Text des Benutzers benutzerdefinierten Funktion.</value>
        <remarks>Dies muss eine gültige JavaScript-Funktion z. B. "Function (Eingabe) {return input.toLowerCase();}" sein.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>