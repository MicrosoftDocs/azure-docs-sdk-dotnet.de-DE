<Type Name="AdminKeysOperationsExtensions" FullName="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AdminKeysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AdminKeysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AdminKeysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AdminKeysOperationsExtensions = class" />
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
            Erweiterungsmethoden für AdminKeysOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.AdminKeyResult Get (this Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.AdminKeyResult Get(class Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.Get(Microsoft.Azure.Management.Search.IAdminKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Search.IAdminKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.AdminKeyResult" Usage="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.Get (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.AdminKeyResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IAdminKeysOperations" RefType="this" />
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
            Ruft den primären und sekundären Administratorschlüssel API-Schlüssel für den angegebenen Azure Search-Dienst ab.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt; GetAsync (this Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt; GetAsync(class Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Search.IAdminKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Search.IAdminKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;" Usage="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.GetAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IAdminKeysOperations" RefType="this" />
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
            Ruft den primären und sekundären Administratorschlüssel API-Schlüssel für den angegebenen Azure Search-Dienst ab.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Regenerate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.AdminKeyResult Regenerate (this Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.AdminKeyResult Regenerate(class Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, valuetype Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.Regenerate(Microsoft.Azure.Management.Search.IAdminKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.AdminKeyKind,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Regenerate : Microsoft.Azure.Management.Search.IAdminKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.AdminKeyKind * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.AdminKeyResult" Usage="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.Regenerate (operations, resourceGroupName, searchServiceName, keyKind, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.AdminKeyResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IAdminKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="keyKind" Type="Microsoft.Azure.Management.Search.Models.AdminKeyKind" />
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
        <param name="keyKind">
            Gibt an, welcher Schlüssel neu generiert werden soll. Gültige Werte sind "primary" und "secondary". Folgende Werte sind möglich: 'primary','sekundären'
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Generiert einen neuen Schlüssel Primär oder sekundär Admin-API. Mit einer Operation kann jeweils nur ein Schlüssel neu generiert werden.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt; RegenerateAsync (this Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt; RegenerateAsync(class Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, valuetype Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.RegenerateAsync(Microsoft.Azure.Management.Search.IAdminKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.AdminKeyKind,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateAsync : Microsoft.Azure.Management.Search.IAdminKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.AdminKeyKind * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;" Usage="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.RegenerateAsync (operations, resourceGroupName, searchServiceName, keyKind, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions/&lt;RegenerateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IAdminKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="keyKind" Type="Microsoft.Azure.Management.Search.Models.AdminKeyKind" />
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
        <param name="keyKind">
            Gibt an, welcher Schlüssel neu generiert werden soll. Gültige Werte sind "primary" und "secondary". Folgende Werte sind möglich: 'primary','sekundären'
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Generiert einen neuen Schlüssel Primär oder sekundär Admin-API. Mit einer Operation kann jeweils nur ein Schlüssel neu generiert werden.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>