<Type Name="IndexersOperationsExtensions" FullName="Microsoft.Azure.Search.IndexersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IndexersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IndexersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IndexersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IndexersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IndexersOperationsExtensions = class" />
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
            Vorgänge zum Verwalten von Indexern. 
            <see href="https://docs.microsoft.com/rest/api/searchservice/Indexer-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Indexer Create (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Indexer Create(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Create(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Create (operations, indexer, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Indexer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexer">
            Die Definition der zu erstellenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Erstellt einen neuen Azure Search-Indexer.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt; CreateAsync (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; CreateAsync(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateAsync(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateAsync (operations, indexer, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;CreateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexer">
            Die Definition der zu erstellenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen neuen Azure Search-Indexer.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Indexer CreateOrUpdate (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Indexer CreateOrUpdate(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdate (operations, indexer, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Indexer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexer">
            Die Definition des Indexers erstellt oder aktualisiert werden soll.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Erstellt einen neuen Azure Search-Indexer oder aktualisiert einen Indexer, wenn sie bereits vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Indexer CreateOrUpdate (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Indexer CreateOrUpdate(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdate (operations, indexerName, indexer, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Indexer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des Indexers erstellt oder aktualisiert werden soll.
            </param>
        <param name="indexer">
            Die Definition des Indexers erstellt oder aktualisiert werden soll.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Erstellt einen neuen Azure Search-Indexer oder aktualisiert einen Indexer, wenn sie bereits vorhanden ist.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdateAsync (operations, indexer, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexer">
            Die Definition des Indexers erstellt oder aktualisiert werden soll.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen neuen Azure Search-Indexer oder aktualisiert einen Indexer, wenn sie bereits vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdateAsync (operations, indexerName, indexer, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des Indexers erstellt oder aktualisiert werden soll.
            </param>
        <param name="indexer">
            Die Definition des Indexers erstellt oder aktualisiert werden soll.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen neuen Azure Search-Indexer oder aktualisiert einen Indexer, wenn sie bereits vorhanden ist.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Delete(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Delete (operations, indexerName, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des zu löschenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht einen Azure Search-Indexer.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Indexer" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.DeleteAsync (operations, indexerName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des zu löschenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Azure Search-Indexer.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Exists(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Exists (operations, indexerName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Legt fest, ob der angegebene Indexer im Azure-Suchdienst vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn der Indexer vorhanden ist. <c>"false"</c> andernfalls.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.ExistsAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt fest, ob der angegebene Indexer im Azure-Suchdienst vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn der Indexer vorhanden ist. <c>"false"</c> andernfalls.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Indexer Get (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Indexer Get(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Get(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Get (operations, indexerName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Indexer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des abzurufenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft eine indexerdefinition aus Azure Search ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt; GetAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; GetAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.GetAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.GetAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des abzurufenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine indexerdefinition aus Azure Search ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexerExecutionInfo GetStatus (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexerExecutionInfo GetStatus(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.GetStatus(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member GetStatus : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexerExecutionInfo" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.GetStatus (operations, indexerName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexerExecutionInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des Indexers, für das Status abgerufen werden sollen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Gibt den aktuellen Status und Ausführungsverlauf eines Indexers zurück.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Indexer-Status" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerExecutionInfo&gt; GetStatusAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexerExecutionInfo&gt; GetStatusAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.GetStatusAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatusAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerExecutionInfo&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.GetStatusAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;GetStatusAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerExecutionInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des Indexers, für das Status abgerufen werden sollen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt den aktuellen Status und Ausführungsverlauf eines Indexers zurück.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Indexer-Status" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexerListResult List (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexerListResult List(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.List(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexerListResult" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.List (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexerListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet alle Indexer für einen Azure Search-Dienst verfügbar.
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexers" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerListResult&gt; ListAsync (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexerListResult&gt; ListAsync(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.ListAsync(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerListResult&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.ListAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Indexer für einen Azure Search-Dienst verfügbar.
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexers" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reset">
      <MemberSignature Language="C#" Value="public static void Reset (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Reset(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Reset(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Reset : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; unit" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Reset (operations, indexerName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des zurückzusetzenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Setzt einen Azure Search-Indexer zugeordneten änderungsnachverfolgungsstatus zurück.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Reset-Indexer" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.ResetAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.ResetAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;ResetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des zurückzusetzenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Setzt einen Azure Search-Indexer zugeordneten änderungsnachverfolgungsstatus zurück.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Reset-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Run">
      <MemberSignature Language="C#" Value="public static void Run (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Run(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Run(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Run : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; unit" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Run (operations, indexerName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des auszuführenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Führt einen Azure Search-Indexer bei Bedarf an.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Run-Indexer" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RunAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RunAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.RunAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RunAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.RunAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;RunAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="indexerName">
            Der Name des auszuführenden Indexers.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Führt einen Azure Search-Indexer bei Bedarf an.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Run-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>