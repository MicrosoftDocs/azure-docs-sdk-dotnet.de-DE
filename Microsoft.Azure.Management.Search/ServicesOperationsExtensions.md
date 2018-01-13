<Type Name="ServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Search.ServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.ServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServicesOperationsExtensions = class" />
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
            Erweiterungsmethoden für ServicesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput CheckNameAvailability (this Microsoft.Azure.Management.Search.IServicesOperations operations, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput CheckNameAvailability(class Microsoft.Azure.Management.Search.IServicesOperations operations, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailability (operations, name, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="name">
            Der Search-Dienst zu überprüfende Name. Suchen von Dienstnamen darf nur Kleinbuchstaben, Ziffern oder Gedankenstriche enthalten, können keine Bindestrich als eines der ersten beiden oder als letztes Zeichen darf keine aufeinanderfolgenden Bindestriche enthalten und müssen zwischen 2 und 60 Zeichen lang sein.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Überprüft, und zwar unabhängig davon, ob der angegebene Dienstname für die Verwendung verfügbar ist.
            Suchen von Dienstnamen müssen global eindeutig sein, da sie Teil des Dienst-URIS sind (https://&lt;Namen&gt;..Search.Windows.NET"lauten).
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailabilityAsync (operations, name, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="name">
            Der Search-Dienst zu überprüfende Name. Suchen von Dienstnamen darf nur Kleinbuchstaben, Ziffern oder Gedankenstriche enthalten, können keine Bindestrich als eines der ersten beiden oder als letztes Zeichen darf keine aufeinanderfolgenden Bindestriche enthalten und müssen zwischen 2 und 60 Zeichen lang sein.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, und zwar unabhängig davon, ob der angegebene Dienstname für die Verwendung verfügbar ist.
            Suchen von Dienstnamen müssen global eindeutig sein, da sie Teil des Dienst-URIS sind (https://&lt;Namen&gt;..Search.Windows.NET"lauten).
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.SearchService CreateOrUpdate (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchService service, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.SearchService CreateOrUpdate(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchService service, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchService,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchService * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, searchServiceName, service, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.SearchService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="service" Type="Microsoft.Azure.Management.Search.Models.SearchService" />
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
            Der Name des Azure-Suchdienst erstellen oder aktualisieren. Suchen von Dienstnamen darf nur Kleinbuchstaben, Ziffern oder Gedankenstriche enthalten, können keine Bindestrich als eines der ersten beiden oder als letztes Zeichen darf keine aufeinanderfolgenden Bindestriche enthalten und müssen zwischen 2 und 60 Zeichen lang sein. Suchen von Dienstnamen müssen global eindeutig sein, da sie Teil des Dienst-URIS sind (https://&lt;Namen&gt;..Search.Windows.NET"lauten). Der Dienstname kann nicht geändert werden, nachdem der Dienst erstellt wird.
            </param>
        <param name="service">
            Die Definition der Search-Dienst erstellt oder aktualisiert.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Erstellt oder aktualisiert einen Search-Dienst in der angegebenen Ressourcengruppe. Wenn der Search-Dienst bereits vorhanden ist, werden alle Eigenschaften mit den angegebenen Werten aktualisiert werden.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchService service, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchService service, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchService,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchService * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, searchServiceName, service, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="service" Type="Microsoft.Azure.Management.Search.Models.SearchService" />
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
            Der Name des Azure-Suchdienst erstellen oder aktualisieren. Suchen von Dienstnamen darf nur Kleinbuchstaben, Ziffern oder Gedankenstriche enthalten, können keine Bindestrich als eines der ersten beiden oder als letztes Zeichen darf keine aufeinanderfolgenden Bindestriche enthalten und müssen zwischen 2 und 60 Zeichen lang sein. Suchen von Dienstnamen müssen global eindeutig sein, da sie Teil des Dienst-URIS sind (https://&lt;Namen&gt;..Search.Windows.NET"lauten). Der Dienstname kann nicht geändert werden, nachdem der Dienst erstellt wird.
            </param>
        <param name="service">
            Die Definition der Search-Dienst erstellt oder aktualisiert.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert einen Search-Dienst in der angegebenen Ressourcengruppe. Wenn der Search-Dienst bereits vorhanden ist, werden alle Eigenschaften mit den angegebenen Werten aktualisiert werden.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Delete(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; unit" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Delete (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
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
            Löscht einen Search-Dienst in der angegebenen Ressourcengruppe sowie die zugehörigen Ressourcen.
            <see href="https://aka.ms/search-manage" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
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
            Löscht einen Search-Dienst in der angegebenen Ressourcengruppe sowie die zugehörigen Ressourcen.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.SearchService Get (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.SearchService Get(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Get(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Get (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.SearchService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
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
            Ruft die Search-Dienst mit dem angegebenen Namen in der angegebenen Ressourcengruppe.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; GetAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; GetAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.GetAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
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
            Ruft die Search-Dienst mit dem angegebenen Namen in der angegebenen Ressourcengruppe.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; ListByResourceGroup (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; ListByResourceGroup(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; seq&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements. Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft eine Liste aller Suchdienste in der angegebenen Ressourcengruppe ab.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
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
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste aller Suchdienste in der angegebenen Ressourcengruppe ab.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>