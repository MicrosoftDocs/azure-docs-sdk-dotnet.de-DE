<Type Name="IAdminKeysOperations" FullName="Microsoft.Azure.Management.Search.IAdminKeysOperations">
  <TypeSignature Language="C#" Value="public interface IAdminKeysOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAdminKeysOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.IAdminKeysOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAdminKeysOperations" />
  <TypeSignature Language="F#" Value="type IAdminKeysOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            AdminKeysOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IAdminKeysOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;&gt;" Usage="iAdminKeysOperations.GetWithHttpMessagesAsync (resourceGroupName, searchServiceName, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.
            Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
            </param>
        <param name="searchServiceName">
            Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.
            </param>
        <param name="searchManagementRequestOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den primären und sekundären Administratorschlüssel API-Schlüssel für den angegebenen Azure Search-Dienst ab.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;&gt; RegenerateWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;&gt; RegenerateWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, valuetype Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IAdminKeysOperations.RegenerateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Search.Models.AdminKeyKind,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Search.Models.AdminKeyKind * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;&gt;" Usage="iAdminKeysOperations.RegenerateWithHttpMessagesAsync (resourceGroupName, searchServiceName, keyKind, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="keyKind" Type="Microsoft.Azure.Management.Search.Models.AdminKeyKind" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.
            Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.
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
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Generiert einen neuen Schlüssel Primär oder sekundär Admin-API. Mit einer Operation kann jeweils nur ein Schlüssel neu generiert werden.
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>