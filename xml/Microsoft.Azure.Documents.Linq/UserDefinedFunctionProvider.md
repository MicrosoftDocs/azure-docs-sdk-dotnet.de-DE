<Type Name="UserDefinedFunctionProvider" FullName="Microsoft.Azure.Documents.Linq.UserDefinedFunctionProvider">
  <TypeSignature Language="C#" Value="public static class UserDefinedFunctionProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UserDefinedFunctionProvider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Linq.UserDefinedFunctionProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class UserDefinedFunctionProvider" />
  <TypeSignature Language="F#" Value="type UserDefinedFunctionProvider = class" />
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
            <span data-ttu-id="5a1f9-101">Hilfsklasse zum Aufrufen von benutzerdefinierten Funktionen über Linq-Abfragen in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="5a1f9-101">Helper class to invoke User Defined Functions via Linq queries in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invoke">
      <MemberSignature Language="C#" Value="public static object Invoke (string udfName, params object[] arguments);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig object Invoke(string udfName, object[] arguments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.UserDefinedFunctionProvider.Invoke(System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Invoke (udfName As String, ParamArray arguments As Object()) As Object" />
      <MemberSignature Language="F#" Value="static member Invoke : string * obj[] -&gt; obj" Usage="Microsoft.Azure.Documents.Linq.UserDefinedFunctionProvider.Invoke (udfName, arguments)" />
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="udfName" Type="System.String" />
        <Parameter Name="arguments" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="udfName"><span data-ttu-id="5a1f9-102">der Name des UserDefinedFunction</span><span class="sxs-lookup"><span data-stu-id="5a1f9-102">the UserDefinedFunction name</span></span></param>
        <param name="arguments"><span data-ttu-id="5a1f9-103">die Argumente des UserDefinedFunction</span><span class="sxs-lookup"><span data-stu-id="5a1f9-103">the arguments of the UserDefinedFunction</span></span></param>
        <summary>
            <span data-ttu-id="5a1f9-104">Hilfsmethode zum Aufrufen von benutzerdefinierten Funktionen über Linq-Abfragen in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="5a1f9-104">Helper method to invoke User Defined Functions via Linq queries in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns />
        <remarks>
            <span data-ttu-id="5a1f9-105">Dies ist eine Hilfsmethode Stub für die Verwendung in LINQ-Ausdrücke.</span><span class="sxs-lookup"><span data-stu-id="5a1f9-105">This is a stub helper method for use within LINQ expressions.</span></span> <span data-ttu-id="5a1f9-106">Kann nicht direkt aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="5a1f9-106">Cannot be called directly.</span></span> <span data-ttu-id="5a1f9-107">Verweisen Sie auf Weitere Details zu der LINQ-Anbieter http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#linq-to-documentdb-sql.</span><span class="sxs-lookup"><span data-stu-id="5a1f9-107">Refer to http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#linq-to-documentdb-sql for more details about the LINQ provider.</span></span>
            <span data-ttu-id="5a1f9-108">Http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration für ausführliche Informationen zu benutzerdefinierten Funktionen finden Sie unter.</span><span class="sxs-lookup"><span data-stu-id="5a1f9-108">Refer to http://azure.microsoft.com/documentation/articles/documentdb-sql-query/#javascript-integration for more details about user defined functions.</span></span>
            </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />
        <example>
          <code language="c#"><![CDATA[
             await client.CreateUserDefinedFunctionAsync(collectionLink, new UserDefinedFunction { Id = "calculateTax", Body = @"function(amt) { return amt * 0.05; }" });
             var queryable = client.CreateDocumentQuery<Book>(collectionLink).Select(b => UserDefinedFunctionProvider.Invoke("calculateTax", b.Price));
             
            // Equivalent to SELECT * FROM books b WHERE udf.toLowerCase(b.title) = 'war and peace'" 
            await client.CreateUserDefinedFunctionAsync(collectionLink, new UserDefinedFunction { Id = "toLowerCase", Body = @"function(s) { return s.ToLowerCase(); }" });
            queryable = client.CreateDocumentQuery<Book>(collectionLink).Where(b => UserDefinedFunctionProvider.Invoke("toLowerCase", b.Title) == "war and peace");
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>