<Type Name="IAccountOperations" FullName="Microsoft.Azure.Batch.Protocol.IAccountOperations">
  <TypeSignature Language="C#" Value="public interface IAccountOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAccountOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IAccountOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAccountOperations" />
  <TypeSignature Language="F#" Value="type IAccountOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            AccountOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListNodeAgentSkusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt; ListNodeAgentSkusNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions accountListNodeAgentSkusNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt; ListNodeAgentSkusNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions accountListNodeAgentSkusNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IAccountOperations.ListNodeAgentSkusNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNodeAgentSkusNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt;" Usage="iAccountOperations.ListNodeAgentSkusNextWithHttpMessagesAsync (nextPageLink, accountListNodeAgentSkusNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="accountListNodeAgentSkusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="accountListNodeAgentSkusNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Knoten-Agent-SKUs von der Azure Batch-Dienst unterstützt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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
    <Member MemberName="ListNodeAgentSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt; ListNodeAgentSkusWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions accountListNodeAgentSkusOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;, class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt; ListNodeAgentSkusWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions accountListNodeAgentSkusOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IAccountOperations.ListNodeAgentSkusWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNodeAgentSkusWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;, Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt;" Usage="iAccountOperations.ListNodeAgentSkusWithHttpMessagesAsync (accountListNodeAgentSkusOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku&gt;,Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountListNodeAgentSkusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.AccountListNodeAgentSkusOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountListNodeAgentSkusOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Knoten-Agent-SKUs von der Azure Batch-Dienst unterstützt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
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