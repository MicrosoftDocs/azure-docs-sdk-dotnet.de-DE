<Type Name="IDataFactoryManagementClient" FullName="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient">
  <TypeSignature Language="C#" Value="public interface IDataFactoryManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataFactoryManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataFactoryManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IDataFactoryManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivityTypes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IActivityTypeOperations ActivityTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IActivityTypeOperations ActivityTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ActivityTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityTypes As IActivityTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityTypes : Microsoft.Azure.Management.DataFactories.Core.IActivityTypeOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ActivityTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IActivityTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Data Factory "activitytypes".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityWindows">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations ActivityWindows { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations ActivityWindows" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ActivityWindows" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityWindows As IActivityWindowOperations" />
      <MemberSignature Language="F#" Value="member this.ActivityWindows : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ActivityWindows" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge für das Aktivitätsfenster.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der URI, der als Basis für alle Service Management-Anforderungen verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeTypes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations ComputeTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations ComputeTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ComputeTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputeTypes As IComputeTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ComputeTypes : Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.ComputeTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IComputeTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Data Factory ComputeTypes.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Wenn Sie einen Windows Azure-Abonnement erstellen, wird er eindeutig durch eine Abonnement-ID identifiziert. Die Abonnement-ID ist Teil der URI für jeden Aufruf, die Sie an die Dienstverwaltungs-API vornehmen. Der Windows Azure-Dienst ManagementAPI verwenden gegenseitige Authentifizierung von verwaltungszertifikaten über SSL, um sicherzustellen, dass eine Anforderung an den Dienst sicher ist. Keine anonyme Anforderungen sind zulässig.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataFactories">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations DataFactories { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations DataFactories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataFactories" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataFactories As IDataFactoryOperations" />
      <MemberSignature Language="F#" Value="member this.DataFactories : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataFactories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Data Factorys.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Datasets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations Datasets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations Datasets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Datasets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Datasets As IDatasetOperations" />
      <MemberSignature Language="F#" Value="member this.Datasets : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Datasets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Datasets.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSliceRuns">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations DataSliceRuns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations DataSliceRuns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataSliceRuns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSliceRuns As IDataSliceRunOperations" />
      <MemberSignature Language="F#" Value="member this.DataSliceRuns : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataSliceRuns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Daten Slice ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSlices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations DataSlices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations DataSlices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataSlices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSlices As IDataSliceOperations" />
      <MemberSignature Language="F#" Value="member this.DataSlices : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.DataSlices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Datenslices.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Gateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations Gateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations Gateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Gateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Gateways As IGatewayOperations" />
      <MemberSignature Language="F#" Value="member this.Gateways : Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Gateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Data Factory-Gateways.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLongRunningOperationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; GetLongRunningOperationStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; GetLongRunningOperationStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.GetLongRunningOperationStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetLongRunningOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iDataFactoryManagementClient.GetLongRunningOperationStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
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
        <summary>
            Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück. Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.
            </summary>
        <returns>
            Eine standarddienstantwort für lang ausgeführte Vorgänge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hubs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IHubOperations Hubs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IHubOperations Hubs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Hubs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Hubs As IHubOperations" />
      <MemberSignature Language="F#" Value="member this.Hubs : Microsoft.Azure.Management.DataFactories.Core.IHubOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Hubs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IHubOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Hubs.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations LinkedServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations LinkedServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LinkedServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinkedServices As ILinkedServiceOperations" />
      <MemberSignature Language="F#" Value="member this.LinkedServices : Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LinkedServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.ILinkedServiceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Data Factory interne LinkedServices.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das ursprüngliche Timeout für zeitintensive Vorgänge.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das wiederholungstimeout für zeitintensive Vorgänge.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OAuth">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations OAuth { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations OAuth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.OAuth" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OAuth As IOAuthOperations" />
      <MemberSignature Language="F#" Value="member this.OAuth : Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.OAuth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IOAuthOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge für das OAuth-autorisierungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipelines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations Pipelines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations Pipelines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Pipelines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Pipelines As IPipelineOperations" />
      <MemberSignature Language="F#" Value="member this.Pipelines : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" Usage="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryManagementClient.Pipelines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Vorgänge zum Verwalten von Pipelines.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>