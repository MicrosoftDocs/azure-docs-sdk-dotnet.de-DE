<Type Name="SynonymMapsOperationsExtensions" FullName="Microsoft.Azure.Search.SynonymMapsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SynonymMapsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SynonymMapsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.SynonymMapsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SynonymMapsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SynonymMapsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Vorgänge zum Verwalten von Synonymmaps. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMap Create (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMap Create(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Create(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Create (operations, synonymMap, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMap">
            Die Definition der Zuordnung Synonym zu erstellen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Erstellt eine neue Azure Search Synonym.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; CreateAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; CreateAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateAsync(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateAsync (operations, synonymMap, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;CreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMap">
            Die Definition der Zuordnung Synonym zu erstellen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine neue Azure Search Synonym.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMap CreateOrUpdate (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMap CreateOrUpdate(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdate (operations, synonymMap, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMap">
            Die Definition der Synonymmap erstellt oder aktualisiert.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Erstellt eine neue Azure Search Synonymmap oder eine Synonymmap aktualisiert, wenn sie bereits vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMap CreateOrUpdate (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMap CreateOrUpdate(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdate (operations, synonymMapName, synonymMap, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMapName">
            Der Name der Zuordnung Synonym erstellt oder aktualisiert werden soll.
            </param>
        <param name="synonymMap">
            Die Definition der Zuordnung Synonym erstellt oder aktualisiert werden soll.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Erstellt eine neue Azure Search Synonym Karte oder eine Karte Synonym aktualisiert, wenn sie bereits vorhanden ist.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdateAsync (operations, synonymMap, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMap">
            Die Definition der Synonymmap erstellt oder aktualisiert.
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
            Erstellt eine neue Azure Search Synonymmap oder eine Synonymmap aktualisiert, wenn sie bereits vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdateAsync (operations, synonymMapName, synonymMap, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMapName">
            Der Name der Zuordnung Synonym erstellt oder aktualisiert werden soll.
            </param>
        <param name="synonymMap">
            Die Definition der Zuordnung Synonym erstellt oder aktualisiert werden soll.
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
            Erstellt eine neue Azure Search Synonym Karte oder eine Karte Synonym aktualisiert, wenn sie bereits vorhanden ist.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Delete(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Delete (operations, synonymMapName, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMapName">
            Der Name der Zuordnung Synonym löschen.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="accessCondition">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht eine Azure Search Synonym Zuordnung an.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Synonym-Map" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.DeleteAsync (operations, synonymMapName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMapName">
            Der Name der Zuordnung Synonym löschen.
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
            Löscht eine Azure Search Synonym Zuordnung an.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Exists(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Exists (operations, synonymMapName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMapName">
            Der Name der Zuordnung Synonym.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Legt fest, ob die Zuordnung angegebenen Synonym in der Azure Search-Dienst vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn das Synonym Zuordnung vorhanden ist. <c>"false"</c> andernfalls.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.ExistsAsync (operations, synonymMapName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMapName">
            Der Name der Zuordnung Synonym.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt fest, ob die Zuordnung angegebenen Synonym in der Azure Search-Dienst vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn das Synonym Zuordnung vorhanden ist. <c>"false"</c> andernfalls.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMap Get (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMap Get(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Get(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Get (operations, synonymMapName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMapName">
            Der Name der abzurufenden Zuordnung Synonym.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft die Definition eines Synonym-Zuordnung aus Azure Search ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; GetAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; GetAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.GetAsync(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.GetAsync (operations, synonymMapName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="synonymMapName">
            Der Name der abzurufenden Zuordnung Synonym.
            </param>
        <param name="searchRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Definition eines Synonym-Zuordnung aus Azure Search ab.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMapListResult List (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMapListResult List(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.List(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.SynonymMapListResult" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.List (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMapListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
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
            Listet alle Synonym Zuordnungen für einen Azure Search-Dienst verfügbar.
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Synonym-Maps" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt; ListAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMapListResult&gt; ListAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.ListAsync(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.ListAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
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
            Listet alle Synonym Zuordnungen für einen Azure Search-Dienst verfügbar.
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Synonym-Maps" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>