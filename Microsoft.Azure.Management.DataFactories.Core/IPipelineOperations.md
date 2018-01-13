<Type Name="IPipelineOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations">
  <TypeSignature Language="C#" Value="public interface IPipelineOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPipelineOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPipelineOperations" />
  <TypeSignature Language="F#" Value="type IPipelineOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Vorgänge zum Verwalten von Pipelines.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="parameters">
            Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen oder Aktualisieren einer Pipeline-Instanz.
            </summary>
        <returns>
            Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataPipelineName">
            Eine eindeutige Pipeline-Instanzname.
            </param>
        <param name="parameters">
            Die Parameter zum Erstellen einer Pipeline erforderlich sind.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie eine neue Pipelineinstanz mit unformatierten Json-Inhalt.
            </summary>
        <returns>
            Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iPipelineOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataPipelineName">
            Der Name der Datenpipeline.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Löschen einer Pipelineinstanz.
            </summary>
        <returns>
            Eine standarddienstantwort für lang ausgeführte Vorgänge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="parameters">
            Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen oder Aktualisieren einer Pipeline-Instanz.
            </summary>
        <returns>
            Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataPipelineName">
            Eine eindeutige Pipeline-Instanzname.
            </param>
        <param name="parameters">
            Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Erstellen Sie eine neue Pipelineinstanz mit unformatierten Json-Inhalt.
            </summary>
        <returns>
            Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iPipelineOperations.DeleteAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataPipelineName">
            Der Name der Datenpipeline.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Löschen einer Pipelineinstanz.
            </summary>
        <returns>
            Eine standarddienstantwort für lang ausgeführte Vorgänge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;" Usage="iPipelineOperations.GetAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataPipelineName">
            Der Name der Datenpipeline.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft eine Pipelineinstanz ab.
            </summary>
        <returns>
            Get Pipeline Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>To be added.</summary>
        <returns>
            Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="iPipelineOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die erste Seite des Pipelineinstanzen mit dem Link zur nächsten Seite ab.
            </summary>
        <returns>
            Liste Pipeline Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="iPipelineOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            Die Url zur nächsten Seite Pipelines.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Ruft die nächste Seite der Pipelineinstanzen mit dem Link zur nächsten Seite ab.
            </summary>
        <returns>
            Liste Pipeline Antworten für den Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ResumeAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.ResumeAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
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
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataPipelineName">
            Der Name der Datenpipeline.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Fortsetzen einer angehaltenen Pipeline.
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetActivePeriodAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.SetActivePeriodAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetActivePeriodAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.SetActivePeriodAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
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
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataPipelineName">
            Der Name der Datenpipeline.
            </param>
        <param name="parameters">
            Der Parameter erforderlich, um den aktiven Zeitraum einer Pipeline festgelegt.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Legt den aktiven Zeitraum einer Pipeline fest.
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.SuspendAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.SuspendAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
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
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            Der Ressourcengruppenname der Data Factory.
            </param>
        <param name="dataFactoryName">
            Eine eindeutige Data Factory-Instanzname.
            </param>
        <param name="dataPipelineName">
            Der Name der Datenpipeline.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Anhalten einer Pipeline ausgeführten.
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>