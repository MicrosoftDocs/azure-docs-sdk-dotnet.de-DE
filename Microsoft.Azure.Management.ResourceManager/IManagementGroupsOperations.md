<Type Name="IManagementGroupsOperations" FullName="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IManagementGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IManagementGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IManagementGroupsOperations" />
  <TypeSignature Language="F#" Value="type IManagementGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ManagementGroupsOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;&gt; GetWithHttpMessagesAsync (string expand = null, Nullable&lt;bool&gt; recurse = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;&gt; GetWithHttpMessagesAsync(string expand, valuetype System.Nullable`1&lt;bool&gt; recurse, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations.GetWithHttpMessagesAsync(System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;&gt;" Usage="iManagementGroupsOperations.GetWithHttpMessagesAsync (expand, recurse, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="recurse" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="expand">
             Die $expand-= untergeordnetes Element Abfragezeichenfolgen-Parameter Clients Anforderung Aufnahme der untergeordneten Elemente in der antwortnutzlast kann. Folgende Werte sind möglich: "untergeordnete Elemente"
             </param>
        <param name="recurse">
             Die $recurse = "true" Abfrage Zeichenfolgenparameter ermöglicht Clients die Einbindung der gesamten Hierarchie in der antwortnutzlast anfordern.
             </param>
        <param name="customHeaders">
             Die Header, die hinzugefügt werden auf Anforderung.
             </param>
        <param name="cancellationToken">
             Das Abbruchtoken.
             </param>
        <summary>
             Abrufen von Details der Verwaltungsgruppe.
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
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
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt;" Usage="iManagementGroupsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
             Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
             </param>
        <param name="customHeaders">
             Die Header, die hinzugefügt werden auf Anforderung.
             </param>
        <param name="cancellationToken">
             Das Abbruchtoken.
             </param>
        <summary>
             Liste der Verwaltungsgruppen für den authentifizierten Benutzer.
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
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
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt; ListWithHttpMessagesAsync (string skiptoken = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt; ListWithHttpMessagesAsync(string skiptoken, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt;" Usage="iManagementGroupsOperations.ListWithHttpMessagesAsync (skiptoken, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="skiptoken">
             Fortsetzungstoken für die Seite wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.
             Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen tokenparameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.
             
             </param>
        <param name="customHeaders">
             Die Header, die hinzugefügt werden auf Anforderung.
             </param>
        <param name="cancellationToken">
             Das Abbruchtoken.
             </param>
        <summary>
             Liste der Verwaltungsgruppen für den authentifizierten Benutzer.
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
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