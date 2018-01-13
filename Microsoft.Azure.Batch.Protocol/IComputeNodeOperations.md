<Type Name="IComputeNodeOperations" FullName="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations">
  <TypeSignature Language="C#" Value="public interface IComputeNodeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IComputeNodeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IComputeNodeOperations" />
  <TypeSignature Language="F#" Value="type IComputeNodeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ComputeNodeOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt; AddUserWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt; AddUserWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.AddUserWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddUserWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.AddUserWithHttpMessagesAsync (poolId, nodeId, user, computeNodeAddUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser" />
        <Parameter Name="computeNodeAddUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto erstellen möchten.
            </param>
        <param name="user">
            Das Benutzerkonto erstellt werden soll.
            </param>
        <param name="computeNodeAddUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt ein Benutzerkonto mit dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Knoten nur, wenn es in den Status im Leerlauf befindlichen oder ausgeführten ist ein Benutzerkonto hinzufügen.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt; DeleteUserWithHttpMessagesAsync (string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt; DeleteUserWithHttpMessagesAsync(string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.DeleteUserWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.DeleteUserWithHttpMessagesAsync (poolId, nodeId, userName, computeNodeDeleteUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="computeNodeDeleteUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto löschen möchten.
            </param>
        <param name="userName">
            Der Name des Benutzerkontos zu löschen.
            </param>
        <param name="computeNodeDeleteUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Benutzerkonto aus dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können ein Benutzerkonto auf einen Knoten löschen, nur, wenn sie den Status im Leerlauf befindet oder ausgeführt wird.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableSchedulingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt; DisableSchedulingWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt; DisableSchedulingWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.DisableSchedulingWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableSchedulingWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt;" Usage="iComputeNodeOperations.DisableSchedulingWithHttpMessagesAsync (poolId, nodeId, nodeDisableSchedulingOption, computeNodeDisableSchedulingOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeDisableSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="computeNodeDisableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, auf dem Sie die aufgabenplanung deaktivieren möchten.
            </param>
        <param name="nodeDisableSchedulingOption">
            Was möchten Sie mit den derzeit ausgeführten Aufgaben bei der Deaktivierung der aufgabenplanung auf dem Computeknoten. Der Standardwert ist „requeue“.
            Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion"
            </param>
        <param name="computeNodeDisableSchedulingOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktiviert die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können Aufgabenplanungsdienstes auf einem Knoten nur, wenn aktuelle scheduling Zustand aktiviert ist, deaktivieren.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableSchedulingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt; EnableSchedulingWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt; EnableSchedulingWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.EnableSchedulingWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableSchedulingWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt;" Usage="iComputeNodeOperations.EnableSchedulingWithHttpMessagesAsync (poolId, nodeId, computeNodeEnableSchedulingOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeEnableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, auf dem Sie die aufgabenplanung aktivieren möchten.
            </param>
        <param name="computeNodeEnableSchedulingOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ermöglicht die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können Aufgabenplanungsdienstes auf einem Knoten nur, wenn aktuelle scheduling Zustand deaktiviert ist
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteDesktopWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt; GetRemoteDesktopWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class System.IO.Stream, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt; GetRemoteDesktopWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetRemoteDesktopWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRemoteDesktopWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetRemoteDesktopWithHttpMessagesAsync (poolId, nodeId, computeNodeGetRemoteDesktopOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.IO.Stream,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteDesktopOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, die für den Remotedesktopprotokoll-Datei abgerufen werden soll.
            </param>
        <param name="computeNodeGetRemoteDesktopOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Remotedesktopprotokoll-Datei für den angegebenen Computeknoten ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Bevor Sie einen Knoten mithilfe der RDP-Datei zugreifen können, müssen Sie ein Benutzerkonto auf dem Knoten erstellen. Diese API kann nur auf mit einer Cloud-Service-Konfiguration erstellten Ressourcenpools aufgerufen werden. Mit einer VM-Konfiguration erstellten Ressourcenpools finden Sie unter der GetRemoteLoginSettings-API.
            </remarks>
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
    <Member MemberName="GetRemoteLoginSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt; GetRemoteLoginSettingsWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt; GetRemoteLoginSettingsWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetRemoteLoginSettingsWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRemoteLoginSettingsWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetRemoteLoginSettingsWithHttpMessagesAsync (poolId, nodeId, computeNodeGetRemoteLoginSettingsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteLoginSettingsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens für die remote-Anmelde-Einstellungen abzurufen.
            </param>
        <param name="computeNodeGetRemoteLoginSettingsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Bevor Sie Remote können anmelden auf einen Knoten mithilfe der remote-Anmelde-Einstellungen müssen Sie ein Benutzerkonto erstellen, auf dem Knoten. Diese API kann nur auf mit der Eigenschaft der virtuellen Maschine Konfiguration erstellten Ressourcenpools aufgerufen werden. Finden Sie mit einer Cloud-Service-Konfiguration erstellten Ressourcenpools in der GetRemoteDesktop-API.
            </remarks>
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
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;" Usage="iComputeNodeOperations.GetWithHttpMessagesAsync (poolId, nodeId, computeNodeGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die zu dem Informationen abgerufen werden sollen.
            </param>
        <param name="computeNodeGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Computeknoten ab.
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
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;" Usage="iComputeNodeOperations.ListNextWithHttpMessagesAsync (nextPageLink, computeNodeListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="computeNodeListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="computeNodeListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Serverknoten in den angegebenen Pool.
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
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt; ListWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;" Usage="iComputeNodeOperations.ListWithHttpMessagesAsync (poolId, computeNodeListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, aus der Listenknoten werden sollen.
            </param>
        <param name="computeNodeListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Serverknoten in den angegebenen Pool.
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
    <Member MemberName="RebootWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt; RebootWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt; RebootWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.RebootWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebootWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;" Usage="iComputeNodeOperations.RebootWithHttpMessagesAsync (poolId, nodeId, nodeRebootOption, computeNodeRebootOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeRebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;" />
        <Parameter Name="computeNodeRebootOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die neu gestartet werden soll.
            </param>
        <param name="nodeRebootOption">
            Wann Serverknoten neu starten, und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion", "RetainedData"
            </param>
        <param name="computeNodeRebootOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Startet die angegebene Serverknoten neu.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Knoten nur, wenn es in einem im Leerlauf befindlichen oder ausgeführten Zustand neu starten.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReimageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt; ReimageWithHttpMessagesAsync (string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt; ReimageWithHttpMessagesAsync(string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.ReimageWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt;" Usage="iComputeNodeOperations.ReimageWithHttpMessagesAsync (poolId, nodeId, nodeReimageOption, computeNodeReimageOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeReimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;" />
        <Parameter Name="computeNodeReimageOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die neu gestartet werden soll.
            </param>
        <param name="nodeReimageOption">
            Wann reimaging dem Computeknoten und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion", "RetainedData"
            </param>
        <param name="computeNodeReimageOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Neuinstallation des Betriebssystems auf den angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können das Betriebssystem auf einem Knoten neu installieren, nur dann, wenn es in einem im Leerlauf befindlichen oder ausgeführten Zustand befindet. Diese API kann nur auf mit der Cloud-Dienstkonfigurationseigenschaft erstellten Ressourcenpools aufgerufen werden.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt; UpdateUserWithHttpMessagesAsync (string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt; UpdateUserWithHttpMessagesAsync(string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IComputeNodeOperations.UpdateUserWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateUserWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt;" Usage="iComputeNodeOperations.UpdateUserWithHttpMessagesAsync (poolId, nodeId, userName, nodeUpdateUserParameter, computeNodeUpdateUserOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="nodeUpdateUserParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" />
        <Parameter Name="computeNodeUpdateUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto aktualisieren möchten.
            </param>
        <param name="userName">
            Der Name des Benutzerkontos aktualisieren.
            </param>
        <param name="nodeUpdateUserParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="computeNodeUpdateUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das Kennwort und eine Ablaufzeit Zeit eines Benutzerkontos auf den angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dieser Vorgang ersetzt alle aktualisierbaren Eigenschaften des Kontos. Wenn ExpiryTime-Element nicht angegeben ist, wird der aktuelle Wert z. B. mit dem Standardwert nicht links unverändert bleiben sollen ersetzt. Sie können ein Benutzerkonto auf einem Knoten aktualisieren, nur, wenn sie den Status im Leerlauf befindet oder ausgeführt wird.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>