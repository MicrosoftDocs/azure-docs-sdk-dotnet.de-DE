<Type Name="IDataSliceOperations" FullName="Microsoft.Azure.Management.DataFactories.IDataSliceOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDataSliceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Vorgänge zum Verwalten von Datenslices.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
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
            Parameter, die angibt, wie der Datenslices der Tabelle aufgelistet.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die erste Seite des Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.
            </summary>
        <returns>
            Die Liste Datenslices Vorgangsantwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            Die Url der nächsten Datenseite Slices.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die nächste Seite der Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.
            </summary>
        <returns>
            Die Liste Datenslices Vorgangsantwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.SetStatusAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStatusAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDataSliceOperations.SetStatusAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
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
            Die Parameter erforderlich, um den Status der Datenslices festgelegt.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Status des Datenslices festgelegt über einen Zeitraum für eine bestimmte Tabelle.
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>