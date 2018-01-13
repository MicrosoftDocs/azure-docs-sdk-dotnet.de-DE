<Type Name="INameOperations" FullName="Microsoft.Azure.Management.NotificationHubs.INameOperations">
  <TypeSignature Language="C#" Value="public interface INameOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INameOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.INameOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface INameOperations" />
  <TypeSignature Language="F#" Value="type INameOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            NameOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;&gt; CheckAvailabilityWithHttpMessagesAsync (Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;&gt; CheckAvailabilityWithHttpMessagesAsync(class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.INameOperations.CheckAvailabilityWithHttpMessagesAsync(Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckAvailabilityWithHttpMessagesAsync : Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;&gt;" Usage="iNameOperations.CheckAvailabilityWithHttpMessagesAsync (parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            Der Namespacename.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft die Verfügbarkeit des angegebenen Dienstnamespace über alle Azure-Abonnements. Dies ist hilfreich, da der Domänenname basierend auf den Dienstnamespace erstellt wird.
            </summary>
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