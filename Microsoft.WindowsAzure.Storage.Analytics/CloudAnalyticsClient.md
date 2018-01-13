<Type Name="CloudAnalyticsClient" FullName="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient">
  <TypeSignature Language="C#" Value="public sealed class CloudAnalyticsClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CloudAnalyticsClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CloudAnalyticsClient" />
  <TypeSignature Language="F#" Value="type CloudAnalyticsClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Bietet eine clientseitige logische Darstellung für Microsoft Azure-Speicheranalyse an. Dieser Client wird verwendet, zu konfigurieren und Anforderungen für die Speicheranalyse auszuführen.
            </summary>
    <remarks>Der Dienstclient Analytics kapselt die Endpunkte für die BLOB- und -Dienste. Sie kapselt auch Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudAnalyticsClient (Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobStorageUri, class Microsoft.WindowsAzure.Storage.StorageUri tableStorageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobStorageUri As StorageUri, tableStorageUri As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" Usage="new Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient (blobStorageUri, tableStorageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="tableStorageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobStorageUri">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt, das den Blob-Dienstendpunkt, mit der Erstellung des Clients enthält.</param>
        <param name="tableStorageUri">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageUri" /> Objekt, das den tabellendienstendpunkt verwenden Sie zum Erstellen des Clients enthält.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient" /> -Klasse unter Verwendung der angegebenen BLOB- und Dienstendpunkte und Kontoanmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCapacityQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt; CreateCapacityQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt; CreateCapacityQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateCapacityQuery" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCapacityQuery () As TableQuery(Of CapacityEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateCapacityQuery : unit -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt;" Usage="cloudAnalyticsClient.CreateCapacityQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.CapacityEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> -Objekt für die Blob-Dienst Kapazität Tabelle Abfragen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />-Objekt.</returns>
        <remarks>Diese Methode gilt nur für Blob-Dienst zur Verfügung.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateHourMetricsQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateHourMetricsQuery (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateHourMetricsQuery(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateHourMetricsQuery(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateHourMetricsQuery (service As StorageService, location As StorageLocation) As TableQuery(Of MetricsEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateHourMetricsQuery : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;" Usage="cloudAnalyticsClient.CreateHourMetricsQuery (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="location">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt für die Abfrage eine stündliche Metriken-Protokolltabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMinuteMetricsQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateMinuteMetricsQuery (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt; CreateMinuteMetricsQuery(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.CreateMinuteMetricsQuery(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMinuteMetricsQuery (service As StorageService, location As StorageLocation) As TableQuery(Of MetricsEntity)" />
      <MemberSignature Language="F#" Value="member this.CreateMinuteMetricsQuery : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;" Usage="cloudAnalyticsClient.CreateMinuteMetricsQuery (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;Microsoft.WindowsAzure.Storage.Analytics.MetricsEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="location">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt für die Abfrage von einer Minute Metriken-Protokolltabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCapacityTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetCapacityTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetCapacityTable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetCapacityTable" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCapacityTable () As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetCapacityTable : unit -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetCapacityTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die metriktabelle Kapazität für den Blob-Dienst ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHourMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetHourMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHourMetricsTable (service As StorageService) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetHourMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetHourMetricsTable service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <summary>
            Ruft die stündlichen metrikentabelle für den angegebenen Speicherdienst ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHourMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetHourMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetHourMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHourMetricsTable (service As StorageService, location As StorageLocation) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetHourMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetHourMetricsTable (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="location">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</param>
        <summary>
            Ruft die stündlichen metrikentabelle für den angegebenen Speicherdienst ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogDirectory">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetLogDirectory (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory GetLogDirectory(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetLogDirectory(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLogDirectory (service As StorageService) As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="member this.GetLogDirectory : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="cloudAnalyticsClient.GetLogDirectory service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> Objekt, das die Protokolle für den angegebenen Speicherdienst enthält.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMinuteMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetMinuteMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMinuteMetricsTable (service As StorageService) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetMinuteMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetMinuteMetricsTable service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <summary>
            Ruft die Tabelle minütlichen Metriken für den angegebenen Speicherdienst ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMinuteMetricsTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.StorageLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetMinuteMetricsTable(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.StorageLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.GetMinuteMetricsTable(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.StorageLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMinuteMetricsTable (service As StorageService, location As StorageLocation) As CloudTable" />
      <MemberSignature Language="F#" Value="member this.GetMinuteMetricsTable : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.StorageLocation -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudAnalyticsClient.GetMinuteMetricsTable (service, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="location" Type="Microsoft.WindowsAzure.Storage.StorageLocation" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="location">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</param>
        <summary>
            Ruft die Tabelle minütlichen Metriken für den angegebenen Speicherdienst ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogRecords (service As StorageService) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogRecords (service As StorageService, startTime As DateTimeOffset, endTime As Nullable(Of DateTimeOffset)) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="startTime">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das den Beginn des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</param>
        <param name="endTime">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das das Ende des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ListLogRecords(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogRecords(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogRecords : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="cloudAnalyticsClient.ListLogRecords (service, startTime, endTime, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="startTime">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das den Beginn des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</param>
        <param name="endTime">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das das Ende des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogs (service As StorageService) As IEnumerable(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs service" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <summary>
            Gibt eine aufzählbare Auflistung der Protokoll-Blobs, Analytics Protokolldatensätze zurück. Blobs sind verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLogs (service As StorageService, startTime As DateTimeOffset, endTime As Nullable(Of DateTimeOffset)) As IEnumerable(Of ICloudBlob)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, startTime, endTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="startTime">Ein <see cref="T:System.DateTimeOffset" /> Objekt stellt die Startzeit für die Protokolle abgerufen werden sollen.</param>
        <param name="endTime">Ein <see cref="T:System.DateTimeOffset" /> Objekt stellt die Endzeit für die Protokolle abgerufen werden sollen.</param>
        <summary>
            Gibt eine aufzählbare Auflistung der Protokoll-Blobs, Analytics Protokolldatensätze zurück. Blobs sind verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, operations, details, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="operations">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" /> -Enumerationswert, der die Vorgangstypen Protokollierung für das Filtern der Protokoll-Blobs angibt.</param>
        <param name="details">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumerationswert ab, der angibt, ob Blob-Metadaten zurückgegeben werden sollen. Nur <c>keine</c> und <c>Metadaten</c> Werte sind gültig. </param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine aufzählbare Auflistung der Protokoll-Blobs, Analytics Protokolldatensätze zurück. Blobs sind verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> und verzögert abgerufen werden.</returns>
        <remarks>Beachten Sie, Angeben eines Vorgangs für die Protokollierung für den Typ der <paramref name="operations" /> Parameter beliebige Analytics Protokoll-BLOBs, die den Vorgang angegebenen Protokollierung enthält zurück, selbst wenn Protokoll Blob auch andere Arten von Vorgängen für die Protokollierung enthält. Beachten Sie, die derzeit die einzigen unterstützten Werte für die <paramref name="details" /> Parameter sind <c>keine</c> und <c>Metadaten</c>.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLogs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs (Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, DateTimeOffset startTime, Nullable&lt;DateTimeOffset&gt; endTime, Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; ListLogs(valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService service, valuetype System.DateTimeOffset startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations operations, valuetype Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails details, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ListLogs(Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService,System.DateTimeOffset,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations,Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListLogs : Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService * DateTimeOffset * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations * Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" Usage="cloudAnalyticsClient.ListLogs (service, startTime, endTime, operations, details, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="service" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" />
        <Parameter Name="details" Type="Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="service">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.StorageService" />-Enumerationswert.</param>
        <param name="startTime">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das den Beginn des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</param>
        <param name="endTime">Ein <see cref="T:System.DateTimeOffset" /> Objekt, das das Ende des Zeitraums für die Protokolle abgerufen werden sollen darstellt.</param>
        <param name="operations">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.LoggingOperations" /> -Enumerationswert, der die Vorgangstypen Protokollierung für das Filtern der Protokoll-Blobs angibt.</param>
        <param name="details">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobListingDetails" /> -Enumerationswert ab, der angibt, ob Blob-Metadaten zurückgegeben werden sollen. Nur <c>keine</c> und <c>Metadaten</c> Werte sind gültig. </param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine aufzählbare Auflistung der Protokoll-Blobs, Analytics Protokolldatensätze zurück. Blobs sind verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> und verzögert abgerufen werden.</returns>
        <remarks>Beachten Sie, Angeben eines Vorgangs für die Protokollierung für den Typ der <paramref name="operations" /> Parameter beliebige Analytics Protokoll-BLOBs, die den Vorgang angegebenen Protokollierung enthält zurück, selbst wenn Protokoll Blob auch andere Arten von Vorgängen für die Protokollierung enthält. Beachten Sie, die derzeit die einzigen unterstützten Werte für die <paramref name="details" /> Parameter sind <c>keine</c> und <c>Metadaten</c>.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogBlob">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlob (Microsoft.WindowsAzure.Storage.Blob.ICloudBlob logBlob);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlob(class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob logBlob) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlob(Microsoft.WindowsAzure.Storage.Blob.ICloudBlob)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseLogBlob (logBlob As ICloudBlob) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="static member ParseLogBlob : Microsoft.WindowsAzure.Storage.Blob.ICloudBlob -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlob logBlob" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logBlob" Type="Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" />
      </Parameters>
      <Docs>
        <param name="logBlob">Die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> Objekt, aus dem Protokolldatensätze zu analysieren.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogBlobs">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlobs (System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; logBlobs);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogBlobs(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; logBlobs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlobs(System.Collections.Generic.IEnumerable{Microsoft.WindowsAzure.Storage.Blob.ICloudBlob})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ParseLogBlobs (logBlobs As IEnumerable(Of ICloudBlob)) As IEnumerable(Of LogRecord)" />
      <MemberSignature Language="F#" Value="static member ParseLogBlobs : seq&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt; -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogBlobs logBlobs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logBlobs" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.ICloudBlob&gt;" />
      </Parameters>
      <Docs>
        <param name="logBlobs">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.ICloudBlob" /> Objekte, die Protokolldatensätze zu analysieren.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseLogStream">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogStream (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt; ParseLogStream(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogStream(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="static member ParseLogStream : System.IO.Stream -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;" Usage="Microsoft.WindowsAzure.Storage.Analytics.CloudAnalyticsClient.ParseLogStream stream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Analytics.LogRecord&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream">Die <see cref="T:System.IO.Stream" /> Objekt, aus dem Protokolldatensätze zu analysieren.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Protokolldatensätzen Analytics, verzögert abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Analytics.LogRecord" /> und verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>