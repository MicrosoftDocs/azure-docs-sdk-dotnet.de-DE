<Type Name="IContainerLogsOperations" FullName="Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations">
  <TypeSignature Language="C#" Value="public interface IContainerLogsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContainerLogsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContainerLogsOperations" />
  <TypeSignature Language="F#" Value="type IContainerLogsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ContainerLogsOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string containerGroupName, string containerName, Nullable&lt;int&gt; tail = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string containerGroupName, string containerName, valuetype System.Nullable`1&lt;int32&gt; tail, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt;" Usage="iContainerLogsOperations.ListWithHttpMessagesAsync (resourceGroupName, containerGroupName, containerName, tail, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="tail" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="containerGroupName">
            Der Name der Gruppe "Container".
            </param>
        <param name="containerName">
            Der Name der Containerinstanz.
            </param>
        <param name="tail">
            Die Anzahl der Zeilen, die das Ende des Protokolls Instanz Container anzuzeigen. Wenn nicht angegeben, werden alle verfügbaren Protokolle mit bis zu 4 mb angezeigt.
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Rufen Sie die Protokolle für eine Instanz des angegebenen Container.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie die Protokolle für eine Instanz der angegebenen Container in einem angegebenen Ressourcengruppe und die Containergruppe.
            </remarks>
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