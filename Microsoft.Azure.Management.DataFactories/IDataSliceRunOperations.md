<Type Name="IDataSliceRunOperations" FullName="Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceRunOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceRunOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceRunOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceRunOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Vorgänge zum Verwalten von Daten Slice ausgeführt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string runId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string runId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;" Usage="iDataSliceRunOperations.GetAsync (resourceGroupName, dataFactoryName, runId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="runId">
            Eine eindeutige Ausführung Slice-Id.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft eine Instanz Daten Slice ausgeführt werden.
            </summary>
        <returns>
            Die Get-Vorgangsantwort Daten Slice ausgeführt werden.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync (string resourceGroupName, string dataFactoryName, string dataSliceRunId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync(string resourceGroupName, string dataFactoryName, string dataSliceRunId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations.GetLogsAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetLogsAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;" Usage="iDataSliceRunOperations.GetLogsAsync (resourceGroupName, dataFactoryName, dataSliceRunId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataSliceRunId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataSliceRunId">
            Führen Sie ein eindeutigen Datenslice Instanz-Id aus.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die Protokolle für einen Datenslice ausführen ab
            </summary>
        <returns>
            Der Datenslice Protokolle-Get-Antwort-Vorgang ausgeführt wird.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="iDataSliceRunOperations.ListAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="tableName">
            Eine eindeutige Instanz Tabellenname.
            </param>
        <param name="parameters">
            Parameter für die Filter zur Liste der Datenslice angeben, die der Tabelle ausgeführt wird.
            Format.
            </param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Ruft die erste Seite des Datenslice Ausführen von Instanzen mit dem Link zur nächsten Seite ab.
            </summary>
        <returns>
            Der Datenslice Liste führt Vorgangsantwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceRunOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="iDataSliceRunOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            Die Url zu den nächsten Datenslice wird die Seite ausgeführt.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die nächste Seite der ausgeführten Instanzen mit dem Link zur nächsten Seite ab.
            </summary>
        <returns>
            Der Datenslice Liste führt Vorgangsantwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>