<Type Name="ILocationOperations" FullName="Microsoft.Azure.Management.Batch.ILocationOperations">
  <TypeSignature Language="C#" Value="public interface ILocationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILocationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.ILocationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILocationOperations" />
  <TypeSignature Language="F#" Value="type ILocationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            LocationOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string locationName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string locationName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ILocationOperations.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult&gt;&gt;" Usage="iLocationOperations.CheckNameAvailabilityWithHttpMessagesAsync (locationName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.CheckNameAvailabilityResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="locationName">
            Die gewünschte Region namensüberprüfung.
            </param>
        <param name="name">
            Der Name, der Verfügbarkeit zu überprüfen
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob der Name des Batch-Konto in der angegebenen Region verfügbar ist.
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
    <Member MemberName="GetQuotasWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.BatchLocationQuota&gt;&gt; GetQuotasWithHttpMessagesAsync (string locationName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.BatchLocationQuota&gt;&gt; GetQuotasWithHttpMessagesAsync(string locationName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.ILocationOperations.GetQuotasWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetQuotasWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.BatchLocationQuota&gt;&gt;" Usage="iLocationOperations.GetQuotasWithHttpMessagesAsync (locationName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.BatchLocationQuota&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="locationName">
            Der Bereich für die Kontingente für Batch-Dienst abzurufen.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Batch-Dienst-Kontingente für das angegebene Abonnement am angegebenen Speicherort ab.
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