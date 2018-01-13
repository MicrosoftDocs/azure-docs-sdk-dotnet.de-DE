<Type Name="QueryKeysOperationsExtensions" FullName="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class QueryKeysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueryKeysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module QueryKeysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type QueryKeysOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für QueryKeysOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.QueryKey Create (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.QueryKey Create(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Create(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.QueryKey" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Create (operations, resourceGroupName, searchServiceName, name, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.QueryKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="searchServiceName">
            Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.
            </param>
        <param name="name">
            Der Name der neuen Abfrage-API-Schlüssel.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Generiert einen neuen Abfrageschlüssel für den angegebenen Suchdienst. Pro Dienst können Sie bis zu 50 Abfrageschlüssel erstellen.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt; CreateAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt; CreateAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.CreateAsync (operations, resourceGroupName, searchServiceName, name, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="searchServiceName">
            Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.
            </param>
        <param name="name">
            Der Name der neuen Abfrage-API-Schlüssel.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Generiert einen neuen Abfrageschlüssel für den angegebenen Suchdienst. Pro Dienst können Sie bis zu 50 Abfrageschlüssel erstellen.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Delete(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; unit" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Delete (operations, resourceGroupName, searchServiceName, key, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="searchServiceName">
            Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.
            </param>
        <param name="key">
            Der Abfrageschlüssel gelöscht werden soll. Abfrageschlüssel werden anhand des Werts nicht anhand des Namens identifiziert.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht den Schlüssel für die angegebene Abfrage. Im Gegensatz zu Administratorschlüssel werden Abfrageschlüssel nicht neu generiert. Für die Neugenerierung eines Abfrageschlüssels müssen Sie diesen löschen und neu erstellen.
            <see href="https://aka.ms/search-manage" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.DeleteAsync (operations, resourceGroupName, searchServiceName, key, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="searchServiceName">
            Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.
            </param>
        <param name="key">
            Der Abfrageschlüssel gelöscht werden soll. Abfrageschlüssel werden anhand des Werts nicht anhand des Namens identifiziert.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den Schlüssel für die angegebene Abfrage. Im Gegensatz zu Administratorschlüssel werden Abfrageschlüssel nicht neu generiert. Für die Neugenerierung eines Abfrageschlüssels müssen Sie diesen löschen und neu erstellen.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySearchService">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt; ListBySearchService (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt; ListBySearchService(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchService(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListBySearchService : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; seq&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchService (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="searchServiceName">
            Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Gibt die Liste der Abfrage-API-Schlüssel für den angegebenen Azure-Suchdienst zurück.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySearchServiceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; ListBySearchServiceAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; ListBySearchServiceAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchServiceAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySearchServiceAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchServiceAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;ListBySearchServiceAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="searchServiceName">
            Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Gibt die Liste der Abfrage-API-Schlüssel für den angegebenen Azure-Suchdienst zurück.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>