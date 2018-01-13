<Type Name="FabricClient+ClusterManagementClient" FullName="System.Fabric.FabricClient+ClusterManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ClusterManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ClusterManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ClusterManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ClusterManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ClusterManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die Cluster-Verwaltungsclient für Cluster Wartungsvorgänge ausführen.</para>
    </summary>
    <remarks>
      <para>Die <see cref="T:System.Fabric.FabricClient.ClusterManagementClient" /> stellt APIs bereit, welche Hilfe ', um den Cluster als Ganzes verwalten. Hierbei handelt es sich um in der Regel Verwaltungsbefehlen wichtigen Clusterereignisse beispielsweise beim einem Ausfall von Knoten und die Notwendigkeit eines wichtigen wiederhergestellt betreffen.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActivateNodeAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ActivateNodeAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ActivateNodeAsync (nodeName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ActivateNodeAsync : string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ActivateNodeAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Knoten aktiviert werden.</para>
        </param>
        <summary>
          <para>Aktiviert einen Service Fabric-Clusterknoten, der momentan deaktiviert ist.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die asynchrone Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>
                Sobald aktiviert, der Knoten er wieder geeigneten Ziel zum Platzieren neuer Replikate zum wird und geschlossenen Replikate auf dem Knoten werden geöffnet.</para>
          <para>
                Nach Abschluss dieser API impliziert dies, dass die Absicht, aktivieren Sie vom System registriert wurde. Es bedeutet nicht, dass die Aktivierung abgeschlossen ist. Der Status des Vorgangs kann bestimmt werden, mithilfe der <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ActivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActivateNodeAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ActivateNodeAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ActivateNodeAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ActivateNodeAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Knoten aktiviert werden.</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Aktiviert einen Service Fabric-Clusterknoten, der momentan deaktiviert ist.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die asynchrone Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>
                Sobald aktiviert, der Knoten er wieder geeigneten Ziel zum Platzieren neuer Replikate zum wird und geschlossenen Replikate auf dem Knoten werden geöffnet.</para>
          <para>
                Nach Abschluss dieser API impliziert dies, dass die Absicht, aktivieren Sie vom System registriert wurde. Es bedeutet nicht, dass die Aktivierung abgeschlossen ist. Der Status des Vorgangs kann bestimmt werden, mithilfe der <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyClusterPackage">
      <MemberSignature Language="C#" Value="public void CopyClusterPackage (string imageStoreConnectionString, string clusterManifestPath, string clusterManifestPathInImageStore, string codePackagePath, string codePackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyClusterPackage(string imageStoreConnectionString, string clusterManifestPath, string clusterManifestPathInImageStore, string codePackagePath, string codePackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyClusterPackage (imageStoreConnectionString As String, clusterManifestPath As String, clusterManifestPathInImageStore As String, codePackagePath As String, codePackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.CopyClusterPackage : string * string * string * string * string -&gt; unit" Usage="clusterManagementClient.CopyClusterPackage (imageStoreConnectionString, clusterManifestPath, clusterManifestPathInImageStore, codePackagePath, codePackagePathInImageStore)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="clusterManifestPath" Type="System.String" />
        <Parameter Name="clusterManifestPathInImageStore" Type="System.String" />
        <Parameter Name="codePackagePath" Type="System.String" />
        <Parameter Name="codePackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll. In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird. In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore". Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />. 
            </para>
        </param>
        <param name="clusterManifestPath">
          <para>Der vollständige Pfad zu dem Cluster Manifestdatei kopiert werden soll.</para>
        </param>
        <param name="clusterManifestPathInImageStore">
          <para>Der relative Pfad sowie der Dateiname des Ziels in den imagespeicher besitzen. Dieser Parameter ist erforderlich, wenn ClusterManifestPath angegeben wird. Dieser Pfad wird relativ zum Stammverzeichnis in den imagespeicher besitzen erstellt und als Ziel verwendet wird, für die Cluster-manifest-Kopie.</para>
        </param>
        <param name="codePackagePath">
          <para>Der vollständige Pfad zum Service Fabric-Code-Paket kopiert werden soll.</para>
        </param>
        <param name="codePackagePathInImageStore">
          <para>Der relative Pfad sowie der Dateiname des Ziels in den imagespeicher besitzen. Dieser Parameter ist erforderlich, wenn CodePackagePathInImageStore angegeben wird. Dieser Pfad ist relativ zum Stammverzeichnis in der Image Store erstellt und als Ziel verwendet wird, für die Kopie der Code-Paket.</para>
        </param>
        <summary>
          <para>Kopiert die clustermanifestdatei und/oder Service Fabric-Codepaket in den imagespeicher besitzen wird.</para>
        </summary>
        <remarks>
          <para>Manifest Quellpfad für Cluster und Code Quellpfad darf nicht null sein.</para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Auf der Image Store ist eine erforderliche Datei nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store/Dateiverzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeactivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeactivateNodeAsync (string nodeName, System.Fabric.NodeDeactivationIntent deactivationIntent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeactivateNodeAsync(string nodeName, valuetype System.Fabric.NodeDeactivationIntent deactivationIntent) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeactivateNodeAsync (nodeName As String, deactivationIntent As NodeDeactivationIntent) As Task" />
      <MemberSignature Language="F#" Value="member this.DeactivateNodeAsync : string * System.Fabric.NodeDeactivationIntent -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.DeactivateNodeAsync (nodeName, deactivationIntent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="deactivationIntent" Type="System.Fabric.NodeDeactivationIntent" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens zu deaktivieren.</para>
        </param>
        <param name="deactivationIntent">
          <para>Die <see cref="T:System.Fabric.NodeDeactivationIntent" /> zur Deaktivierung des Knotens.</para>
        </param>
        <summary>
          <para>Deaktiviert einen bestimmten Knoten mit dem angegebenen <see cref="T:System.Fabric.NodeDeactivationIntent" />.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die asynchrone Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>
                Nach Abschluss dieser API impliziert dies, dass die Absicht, deaktivieren Sie vom System registriert wurde. Es bedeutet nicht, dass die Deaktivierung abgeschlossen ist. Der Status des Vorgangs kann bestimmt werden, mithilfe der <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API </para>
          <para>
                Sobald die Deaktivierung ausgeführt wird, die Datei deaktivierungsabsicht kann werden "erhöht" aber nicht verringert (z. B. ein Knoten deaktiviert wurde, mit der <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> Absicht kann weiter mit deaktiviert <see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />, aber nicht umgekehrt. Knoten können erneut aktiviert werden, über <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" /> jedes Mal, wenn nach der Deaktivierung werden. Wenn die Deaktivierung nicht abgeschlossen ist. wird dies die Deaktivierung dadurch abgebrochen. Ein Knoten, der ausfällt und wieder hochgefahren während der Deaktivierung müssen immer noch reaktiviert werden, bevor Dienste auf diesem Knoten platziert werden.</para>
          <para>
                Service Fabric stellt sicher, dass diese Deaktivierung einer "sicheren" Prozess ist. Er führt mehrere sicherheitsüberprüfungen (finden Sie unter <see cref="T:System.Fabric.SafetyCheckKind" />), stellen Sie sicher, dass kein Verlust der Verfügbarkeit oder Daten vorhanden ist </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeactivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeactivateNodeAsync (string nodeName, System.Fabric.NodeDeactivationIntent deactivationIntent, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeactivateNodeAsync(string nodeName, valuetype System.Fabric.NodeDeactivationIntent deactivationIntent, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeactivateNodeAsync : string * System.Fabric.NodeDeactivationIntent * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.DeactivateNodeAsync (nodeName, deactivationIntent, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="deactivationIntent" Type="System.Fabric.NodeDeactivationIntent" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens zu deaktivieren.</para>
        </param>
        <param name="deactivationIntent">
          <para>Die <see cref="T:System.Fabric.NodeDeactivationIntent" /> zur Deaktivierung des Knotens.</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Deaktiviert einen bestimmten Knoten mit dem angegebenen <see cref="T:System.Fabric.NodeDeactivationIntent" />.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die asynchrone Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>
                Nach Abschluss dieser API impliziert dies, dass die Absicht, deaktivieren Sie vom System registriert wurde. Es bedeutet nicht, dass die Deaktivierung abgeschlossen ist. Der Status des Vorgangs kann bestimmt werden, mithilfe der <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API </para>
          <para>
                Sobald die Deaktivierung ausgeführt wird, die Datei deaktivierungsabsicht kann werden "erhöht" aber nicht verringert (z. B. ein Knoten deaktiviert wurde, mit der <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> Absicht kann weiter mit deaktiviert <see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />, aber nicht umgekehrt. Knoten können erneut aktiviert werden, über <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" /> jedes Mal, wenn nach der Deaktivierung werden. Wenn die Deaktivierung nicht abgeschlossen ist. wird dies die Deaktivierung dadurch abgebrochen. Ein Knoten, der ausfällt und wieder hochgefahren während der Deaktivierung müssen immer noch reaktiviert werden, bevor Dienste auf diesem Knoten platziert werden.</para>
          <para>
                Service Fabric stellt sicher, dass diese Deaktivierung einer "sicheren" Prozess ist. Er führt mehrere sicherheitsüberprüfungen (finden Sie unter <see cref="T:System.Fabric.SafetyCheckKind" />), stellen Sie sicher, dass kein Verlust der Verfügbarkeit oder Daten vorhanden ist </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Die Konfigurationsdatei des Service Fabric-Cluster als Zeichenfolge ab.</para>
        </summary>
        <returns>
          <para>Die Service Fabric-Cluster-Konfigurationsdatei als Zeichenfolge.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationAsync (apiVersion As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync apiVersion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="apiVersion">API-Version.</param>
        <summary>
          <para>Die Konfigurationsdatei des Service Fabric-Cluster als Zeichenfolge ab.</para>
        </summary>
        <returns>
          <para>Die Service Fabric-Cluster-Konfigurationsdatei als Zeichenfolge.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Konfigurationsdatei des Service Fabric-Cluster als Zeichenfolge ab, mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Der Service Fabric-Cluster-Konfigurationsdatei als eine Zeichenfolge, mit dem angegebenen Timeout und Abbruchtoken.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (string apiVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(string apiVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync (apiVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiVersion">API-Version.</param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Konfigurationsdatei des Service Fabric-Cluster als Zeichenfolge ab, mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Der Service Fabric-Cluster-Konfigurationsdatei als eine Zeichenfolge, mit dem angegebenen Timeout und Abbruchtoken.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationUpgradeStatusAsync () As Task(Of FabricOrchestrationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft den Status einer Aktualisierung läuft ab.
            </summary>
        <returns>FabricOrchestrationUpgradeProgress</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"></param>
        <summary>
            Ruft den Status einer Aktualisierung läuft ab.
            </summary>
        <returns>FabricOrchestrationUpgradeProgress</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationUpgradeStatusAsync (timeout As TimeSpan) As Task(Of FabricOrchestrationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
            Ruft den Status einer Aktualisierung läuft ab.
            </summary>
        <returns>FabricOrchestrationUpgradeProgress</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
            Ruft den Status einer Aktualisierung läuft ab.
            </summary>
        <returns>FabricOrchestrationUpgradeProgress</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterManifestAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft den XML-Inhalt des aktuellen ausgeführten clustermanifest ab.</para>
        </summary>
        <returns>
          <para>Der Cluster-manifest-Inhalt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft den XML-Inhalt des aktuellen ausgeführten clustermanifest ab.</para>
        </summary>
        <returns>
          <para>Der Cluster-manifest-Inhalt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync (System.Fabric.Description.ClusterManifestQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync(class System.Fabric.Description.ClusterManifestQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync(System.Fabric.Description.ClusterManifestQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : System.Fabric.Description.ClusterManifestQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterManifestQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>Gibt zusätzliche Parameter, um zu bestimmen, welche clustermanifest abgerufen.</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft den XML-Inhalt eines Clusters entsprechend den Angaben von Manifest <paramref name="queryDescription" />.</para>
        </summary>
        <returns>
          <para>Der Cluster-manifest-Inhalt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetFabricUpgradeProgressAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetFabricUpgradeProgressAsync () As Task(Of FabricUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetFabricUpgradeProgressAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;" Usage="clusterManagementClient.GetFabricUpgradeProgressAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Gibt den Status eines Service Fabric-Upgrade-Prozesses zurück.</para>
        </summary>
        <returns>
          <para>Der Fortschritt einer Service Fabric-Aktualisierungsprozess.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetFabricUpgradeProgressAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetFabricUpgradeProgressAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;" Usage="clusterManagementClient.GetFabricUpgradeProgressAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Gibt den Status eines Service Fabric-Upgrade-Prozesses zurück.</para>
        </summary>
        <returns>
          <para>Der Fortschritt einer Service Fabric-Aktualisierungsprozess.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetUpgradeOrchestrationServiceStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUpgradeOrchestrationServiceStateAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetUpgradeOrchestrationServiceStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetUpgradeOrchestrationServiceStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Der Dienst zum Service Fabric Upgrade Orchestrierung Status als Zeichenfolge ab.</para>
        </summary>
        <returns>
          <para>Der Dienst zum Service Fabric Upgrade Orchestrierung Status als Zeichenfolge.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetUpgradeOrchestrationServiceStateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetUpgradeOrchestrationServiceStateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetUpgradeOrchestrationServiceStateAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Der Dienst zum Service Fabric Upgrade Orchestrierung Status als Zeichenfolge ab, mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Der Dienst zum Service Fabric Upgrade Orchestrierung Status als Zeichenfolge, mit dem angegebenen Timeout und Abbruchtoken.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveNextFabricUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync (System.Fabric.FabricUpgradeProgress upgradeProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync(class System.Fabric.FabricUpgradeProgress upgradeProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function MoveNextFabricUpgradeDomainAsync (upgradeProgress As FabricUpgradeProgress) As Task" />
      <MemberSignature Language="F#" Value="member this.MoveNextFabricUpgradeDomainAsync : System.Fabric.FabricUpgradeProgress -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.MoveNextFabricUpgradeDomainAsync upgradeProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.FabricUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para>Das Fabric aktualisieren Prozessobjekt verwendet.</para>
        </param>
        <summary>
          <para>Weist die Dienst-Fabric die nächste upgradedomäne im Cluster zu aktualisieren, wenn die aktuelle upgradedomäne abgeschlossen wurde.</para>
        </summary>
        <returns>
          <para>Der upgradedomäne im Cluster.</para>
        </returns>
        <remarks>
          <para>Ähnlich wie <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextFabricUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync (System.Fabric.FabricUpgradeProgress upgradeProgress, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync(class System.Fabric.FabricUpgradeProgress upgradeProgress, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveNextFabricUpgradeDomainAsync : System.Fabric.FabricUpgradeProgress * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.MoveNextFabricUpgradeDomainAsync (upgradeProgress, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.FabricUpgradeProgress" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para>Das Fabric aktualisieren Prozessobjekt verwendet.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Weist Service Fabric aktualisieren Sie die nächste upgradedomäne im Cluster aus, wenn die aktuelle upgradedomäne abgeschlossen wurde, mithilfe des angegebenen Timeout und ein Abbruchtoken, das an.</para>
        </summary>
        <returns>
          <para>Der upgradedomäne im Cluster.</para>
        </returns>
        <remarks>
          <para>Ähnlich wie <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionFabricAsync (string patchFilePath, string clusterManifestFilePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionFabricAsync(string patchFilePath, string clusterManifestFilePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ProvisionFabricAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionFabricAsync (patchFilePath As String, clusterManifestFilePath As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionFabricAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ProvisionFabricAsync (patchFilePath, clusterManifestFilePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="patchFilePath" Type="System.String" />
        <Parameter Name="clusterManifestFilePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="patchFilePath">
          <para>Der Pfad zu den Update-Patch-Datei.</para>
        </param>
        <param name="clusterManifestFilePath">
          <para>Der Pfad zum clustermanifest.</para>
        </param>
        <summary>
          <para>Stellt die Service Fabric.</para>
        </summary>
        <returns>
          <para>Die bereitgestellte Service Fabric.</para>
        </returns>
        <remarks>
          <para>Ein <languageKeyword>null</languageKeyword> Wert ist zulässig, entweder die <paramref name="patchFilePath" /> Parameter oder die <paramref name="clusterManifestFilePath" /> Parameter. Ein <languageKeyword>null</languageKeyword> Wert kann nicht für beide Parameter verwendet werden.</para>
          <para>Dies wird die Patch-Datei und/oder clustermanifestdatei den Speicherort des Image hochladen. Der Speicherort des Bilds wird als eine Konfigurationseinstellung im clustermanifest angegeben, die bei der Erstellung des Clusters bereitgestellt wurde.</para>
          <para>Clustermanifestprüfung erfolgt im Kontext dieses Aufrufs.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionFabricAsync (string patchFilePath, string clusterManifestFilePath, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionFabricAsync(string patchFilePath, string clusterManifestFilePath, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ProvisionFabricAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionFabricAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ProvisionFabricAsync (patchFilePath, clusterManifestFilePath, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="patchFilePath" Type="System.String" />
        <Parameter Name="clusterManifestFilePath" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="patchFilePath">
          <para>Der Pfad zu den Update-Patch-Datei.</para>
        </param>
        <param name="clusterManifestFilePath">
          <para>Der Pfad zum clustermanifest.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Wird für die Fabric-Dienst mithilfe des angegebenen Timeout und ein Abbruchtoken, das bereitgestellt.</para>
        </summary>
        <returns>
          <para>Die bereitgestellte Service Fabric.</para>
        </returns>
        <remarks>
          <para>Ein <languageKeyword>null</languageKeyword> Wert ist zulässig, entweder die <paramref name="patchFilePath" /> Parameter oder die <paramref name="clusterManifestFilePath" /> Parameter. Ein <languageKeyword>null</languageKeyword> Wert kann nicht für beide Parameter verwendet werden.</para>
          <para>Dies wird die Patch-Datei und/oder clustermanifestdatei den Speicherort des Image hochladen. Der Speicherort des Bilds wird als eine Konfigurationseinstellung im clustermanifest angegeben, die bei der Erstellung des Clusters bereitgestellt wurde.</para>
          <para>Clustermanifestprüfung erfolgt im Kontext dieses Aufrufs.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverPartitionAsync (partitionId As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">Die Partitions-Id her</param>
        <summary>
          <para>Zeigt die Service Fabric-Cluster an, dass eine bestimmte Partition Wiederherstellung durchführen, der derzeit in quorumsverlust feststeckt versucht werden soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die Bestätigung der Absicht darstellt.</para>
        </returns>
        <remarks>
          <para>
                Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können. Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">Die Partitions-Id her</param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Zeigt die Service Fabric-Cluster an, dass eine bestimmte Partition Wiederherstellung durchführen, der derzeit in quorumsverlust feststeckt versucht werden soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die Bestätigung der Absicht darstellt.</para>
        </returns>
        <remarks>
          <para>
                Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können. Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverPartitionsAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionsAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Zeigt die Service Fabric-Cluster an, dass alle Dienste (einschließlich Systemdienste) Wiederherstellung durchführen, der derzeit in quorumsverlust hängen versucht werden soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die Bestätigung der Absicht darstellt.</para>
        </returns>
        <remarks>
          <para>
                Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können. Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionsAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionsAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionsAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionsAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionsAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Zeigt die Service Fabric-Cluster an, dass alle Dienste (einschließlich Systemdienste) Wiederherstellung durchführen, der derzeit in quorumsverlust hängen versucht werden soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die Bestätigung der Absicht darstellt.</para>
        </returns>
        <remarks>
          <para>
                Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können. Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverServicePartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverServicePartitionsAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverServicePartitionsAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverServicePartitionsAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverServicePartitionsAsync (serviceName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverServicePartitionsAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverServicePartitionsAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts wiederhergestellt.</para>
        </param>
        <summary>
          <para>Service Fabric-Cluster zeigt, dass es sich bei den angegebenen Dienst Wiederherstellung durchführen, der derzeit in quorumsverlust feststeckt versucht werden soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die Bestätigung der Absicht darstellt.</para>
        </returns>
        <remarks>
          <para>
                Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können. Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverServicePartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverServicePartitionsAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverServicePartitionsAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverServicePartitionsAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverServicePartitionsAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverServicePartitionsAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts wiederhergestellt.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Service Fabric-Cluster zeigt, dass es sich bei den angegebenen Dienst Wiederherstellung durchführen, der derzeit in quorumsverlust feststeckt, mithilfe des angegebenen Timeout und ein Abbruchtoken, das versucht werden soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die Bestätigung der Absicht darstellt.</para>
        </returns>
        <remarks>
          <para>
                Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können. Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverSystemPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverSystemPartitionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverSystemPartitionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverSystemPartitionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverSystemPartitionsAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverSystemPartitionsAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverSystemPartitionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Zeigt die Service Fabric-Cluster an, dass Systemdienste Wiederherstellung durchführen, der derzeit in quorumsverlust hängen versucht werden soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die Bestätigung der Absicht darstellt.</para>
        </returns>
        <remarks>
          <para>
                Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können. Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverSystemPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverSystemPartitionsAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverSystemPartitionsAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverSystemPartitionsAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverSystemPartitionsAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverSystemPartitionsAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Zeigt die Service Fabric-Cluster an, dass Systemdienste Wiederherstellung durchführen, der derzeit in quorumsverlust hängen versucht werden soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die Bestätigung der Absicht darstellt.</para>
        </returns>
        <remarks>
          <para>
                Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können. Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveClusterPackage">
      <MemberSignature Language="C#" Value="public void RemoveClusterPackage (string imageStoreConnectionString, string clusterManifestPathInImageStore, string codePackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveClusterPackage(string imageStoreConnectionString, string clusterManifestPathInImageStore, string codePackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveClusterPackage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveClusterPackage (imageStoreConnectionString As String, clusterManifestPathInImageStore As String, codePackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveClusterPackage : string * string * string -&gt; unit" Usage="clusterManagementClient.RemoveClusterPackage (imageStoreConnectionString, clusterManifestPathInImageStore, codePackagePathInImageStore)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="clusterManifestPathInImageStore" Type="System.String" />
        <Parameter Name="codePackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll. In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird. In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore". Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />. 
            </para>
        </param>
        <param name="clusterManifestPathInImageStore">
          <para>Der relative Pfad der clustermanifestdatei in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />.</para>
        </param>
        <param name="codePackagePathInImageStore">
          <para>Der relative Pfad des Service Fabric-Codepaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />.</para>
        </param>
        <summary>
          <para>Löscht die clustermanifestdatei und/oder Service Fabric-Codepaket aus den imagespeicher besitzen.</para>
        </summary>
        <remarks>
          <para>ClusterManifestPathInImageStore oder CodePackagePathInImageStore-Parameter kann <languageKeyword>null</languageKeyword>. Jedoch nicht beide Zertifikate werden <languageKeyword>null</languageKeyword>.</para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveNodeStateAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveNodeStateAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveNodeStateAsync (nodeName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveNodeStateAsync : string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RemoveNodeStateAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens der dauerhaft verloren gegangen ist.</para>
        </param>
        <summary>
          <para>Gibt an, dass die persistenten Daten eines Knotens (z. B. aufgrund von Fehler auf dem Datenträger, oder reimaging usw.) verloren gegangen ist und diesem Service Fabric alle Dienste oder Statusangaben auf diesem Knoten als verloren und können nicht wiederhergestellt behandeln soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>
                Nachdem ein Knoten ausfällt, Service Fabric wird nachverfolgen Replikate von permanenten Diensten auf diesem Knoten von da auf diesen Status auf diesem Knoten sind.</para>
          <para>
                In Fällen, in dem der Administrator bekannt ist und, dass der persistente Zustand auf einem Knoten dauerhaft verloren gegangen ist, die <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> Methode aufgerufen werden... Service Fabric zu benachrichtigen, die der Zustand auf dem Knoten ist nicht mehr vorhanden (oder der Knoten mit dem Status er hatte nie zurückkehren kann).</para>
          <para>
                Dies weist Service Fabric beim Warten auf diesem Knoten (und alle beibehaltenen Replikate auf diesem Knoten) wiederherstellen zu beenden.</para>
          <para>
                Hinweis: Diese API muss aufgerufen werden, nachdem sie ermittelt haben, dass der Zustand auf diesem Knoten ausgefallen ist. </para>
          <para>
                Wenn diese API aufgerufen wird, und klicken Sie dann der Knoten wieder mit seinen Status intakt ist es nicht definiertes Verhalten</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveNodeStateAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveNodeStateAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveNodeStateAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RemoveNodeStateAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens der dauerhaft verloren gegangen ist.</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Gibt an, dass ein bestimmter Knoten (die ausgefallen ist) tatsächlich verloren hat, und dieser Service Fabric alle Dienste oder Statusangaben auf diesem Knoten als verloren und können nicht wiederhergestellt behandeln soll.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>
                Nachdem ein Knoten ausfällt, Service Fabric wird nachverfolgen Replikate von permanenten Diensten auf diesem Knoten von da auf diesen Status auf diesem Knoten sind.</para>
          <para>
                In Fällen, in dem der Administrator bekannt ist und, dass ein Knoten (und sein Status) dauerhaft verloren gegangen ist, die <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> Methode sollte aufgerufen werden.</para>
          <para>
                Dies weist Service Fabric beim Warten auf diesem Knoten (und alle beibehaltenen Replikate auf diesem Knoten) wiederherstellen zu beenden.</para>
          <para>
                Hinweis: Diese API muss aufgerufen werden, nachdem sie ermittelt haben, dass der Zustand auf diesem Knoten ausgefallen ist. </para>
          <para>
                Wenn diese API aufgerufen wird, und klicken Sie dann der Knoten wieder mit seinen Status intakt ist es nicht definiertes Verhalten</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetPartitionLoadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetPartitionLoadAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResetPartitionLoadAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ResetPartitionLoadAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResetPartitionLoadAsync (partitionId As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.ResetPartitionLoadAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ResetPartitionLoadAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partition als Guid dargestellte Id </para>
        </param>
        <summary>
          <para> 
            Setzt eine bestimmte Partition laden
            </para>
        </summary>
        <returns>
          <para>Der Task, der diese asynchrone Methode zugeordnet wird. </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetPartitionLoadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetPartitionLoadAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResetPartitionLoadAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ResetPartitionLoadAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResetPartitionLoadAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ResetPartitionLoadAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partition als Guid dargestellte Id </para>
        </param>
        <param name="timeout">
          <para> Die Zeitdauer, in dem die asynchrone Methode in der Reihenfolge für die aufzurufende Methode kein Timeout abgeschlossen werden muss.</para>
        </param>
        <param name="cancellationToken">
          <para>Ein Abbruchtoken, das für diese Methode. </para>
        </param>
        <summary>
          <para> 
            Setzt eine bestimmte Partition laden
            </para>
        </summary>
        <returns>
          <para>Der Task, der diese asynchrone Methode zugeordnet wird. </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackFabricUpgradeAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackFabricUpgradeAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RollbackFabricUpgradeAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RollbackFabricUpgradeAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RollbackFabricUpgradeAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RollbackFabricUpgradeAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Rollback für die Service Fabric, um den Vorgang zu aktualisieren.</para>
        </summary>
        <returns>
          <para>Das Rollback Service Fabric so aktualisieren Sie den Vorgang.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackFabricUpgradeAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackFabricUpgradeAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RollbackFabricUpgradeAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RollbackFabricUpgradeAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RollbackFabricUpgradeAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer, die Service Fabric diesen Vorgang definiert, um den Vorgang fortzusetzen, vor der Rückgabe einer Timeoutausnahme ausgelöst werden kann.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Rollback für die Service Fabric, um den Vorgang zu aktualisieren.</para>
        </summary>
        <returns>
          <para>Das Rollback Service Fabric so aktualisieren Sie den Vorgang.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync (string state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync(string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.SetUpgradeOrchestrationServiceStateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetUpgradeOrchestrationServiceStateAsync (state As String) As Task(Of FabricUpgradeOrchestrationServiceState)" />
      <MemberSignature Language="F#" Value="member this.SetUpgradeOrchestrationServiceStateAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;" Usage="clusterManagementClient.SetUpgradeOrchestrationServiceStateAsync state" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state">Status-Eingabe</param>
        <summary>
          <para>Legt den Status der Dienst zum Service Fabric Upgrade Orchestrierung als Zeichenfolge.</para>
        </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync (string state, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync(string state, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.SetUpgradeOrchestrationServiceStateAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SetUpgradeOrchestrationServiceStateAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;" Usage="clusterManagementClient.SetUpgradeOrchestrationServiceStateAsync (state, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="state">Status-Eingabe</param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Legt den Status der Dienst zum Service Fabric Upgrade Orchestrierung als eine Zeichenfolge mithilfe des angegebenen Timeout und ein Abbruchtoken, das fest.</para>
        </summary>
        <returns>
          <para>Der Status der Dienst zum Service Fabric Upgrade Orchestrierung mithilfe des angegebenen Timeout und ein Abbruchtoken.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToggleVerboseServicePlacementHealthReportingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToggleVerboseServicePlacementHealthReportingAsync (enabled As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.ToggleVerboseServicePlacementHealthReportingAsync : bool -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled">
          <para>Ein boolescher Wert, der bei "true" bewirkt, dass reporting wird ein Replikat kann nicht platziert werden. </para>
        </param>
        <summary>
          <para> 
            Schaltet, ob der Cluster Resource Balancer eine Warnung der Integrität meldet, wenn sie ein Replikat platzieren kann.
            </para>
        </summary>
        <returns>
          <para>Der Task, der diese asynchrone Methode zugeordnet wird. </para>
        </returns>
        <remarks>
          <para>Diese Methode zweimal mit dem Wert "false" aufgerufen wird, löscht sie aus dem Arbeitsspeicher die Berichte, die potenziell ausgegeben werden.
            Wenn diese Methode mit dem Wert "true" aufgerufen wird, meldet der Cluster Resource Balancer Integrität Warnung, wenn sie ein Replikat platzieren kann.
            Wenn solche Health-Warnungen, integritätsprüfungen für eine überwachte Upgrades blockiert werden kann die Umschaltfläche deaktiviert. </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToggleVerboseServicePlacementHealthReportingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync (bool enabled, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync(bool enabled, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync(System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ToggleVerboseServicePlacementHealthReportingAsync : bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync (enabled, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="enabled">
          <para>Ein boolescher Wert, der bei "true" bewirkt, dass reporting wird ein Replikat kann nicht platziert werden. </para>
        </param>
        <param name="timeout">
          <para> Die Zeitdauer, in dem die asynchrone Methode in der Reihenfolge für die aufzurufende Methode kein Timeout abgeschlossen werden muss.</para>
        </param>
        <param name="cancellationToken">
          <para>Ein Abbruchtoken, das für diese Methode. </para>
        </param>
        <summary>
          <para> 
            Schaltet, ob der Cluster Resource Balancer eine Warnung der Integrität meldet, wenn sie ein Replikat platzieren kann.
            </para>
        </summary>
        <returns>
          <para>Der Task, der diese asynchrone Methode zugeordnet wird. </para>
        </returns>
        <remarks>
          <para>Diese Methode zweimal mit dem Wert "false" aufgerufen wird, löscht sie aus dem Arbeitsspeicher die Berichte, die potenziell ausgegeben werden.
            Wenn diese Methode mit dem Wert "true" aufgerufen wird, meldet der Cluster Resource Balancer Integrität Warnung, wenn sie ein Replikat platzieren kann.
            Wenn solche Health-Warnungen, integritätsprüfungen für eine überwachte Upgrades blockiert werden, kann die Umschaltfläche deaktiviert. </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionFabricAsync (string codeVersion, string configVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionFabricAsync(string codeVersion, string configVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UnprovisionFabricAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionFabricAsync (codeVersion As String, configVersion As String) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionFabricAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UnprovisionFabricAsync (codeVersion, configVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="configVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersion">
          <para>Die Codeversion Bereitstellung.</para>
        </param>
        <param name="configVersion">
          <para>Die Konfigurationsversion Bereitstellung.</para>
        </param>
        <summary>
          <para>Unprovisions des Dienst-Fabrics.</para>
        </summary>
        <returns>
          <para>Die nicht bereitgestellten Service Fabric.</para>
        </returns>
        <remarks>
          <para>Ein <languageKeyword>null</languageKeyword> Wert ist zulässig, entweder die <paramref name="codeVersion" /> Parameter oder die <paramref name="configVersion" /> Parameter. Ein <languageKeyword>null</languageKeyword> Wert kann nicht für beide Parameter verwendet werden.</para>
          <para>Dadurch wird die Patch-Datei und/oder clustermanifestdatei aus der Image-Speicherort gelöscht. Der Speicherort des Bilds wird als eine Konfigurationseinstellung im clustermanifest angegeben, die bei der Erstellung des Clusters bereitgestellt wurde.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionFabricAsync (string codeVersion, string configVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionFabricAsync(string codeVersion, string configVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UnprovisionFabricAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionFabricAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UnprovisionFabricAsync (codeVersion, configVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="configVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="codeVersion">
          <para>Die Codeversion Bereitstellung.</para>
        </param>
        <param name="configVersion">
          <para>Die Konfigurationsversion Bereitstellung.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Unprovisions der Fabric-Dienst mithilfe des angegebenen Timeout und ein Abbruchtoken.</para>
        </summary>
        <returns>
          <para>Die nicht bereitgestellten Service Fabric.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateFabricUpgradeAsync (System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateFabricUpgradeAsync(class System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateFabricUpgradeAsync (updateDescription As FabricUpgradeUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateFabricUpgradeAsync : System.Fabric.Description.FabricUpgradeUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpdateFabricUpgradeAsync updateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.FabricUpgradeUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para>Beschreibung der neuen Upgrade Parameter angewendet.</para>
        </param>
        <summary>
          <para>Ändert die Upgrade-Parameter, die das Verhalten des aktuellen clusterupgrade beschreiben.</para>
        </summary>
        <returns>
          <para>Das aktuelle clusterupgrade.</para>
        </returns>
        <remarks />
      </Docs>
    </Member>
    <Member MemberName="UpdateFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateFabricUpgradeAsync (System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateFabricUpgradeAsync(class System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateFabricUpgradeAsync : System.Fabric.Description.FabricUpgradeUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpdateFabricUpgradeAsync (updateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.FabricUpgradeUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para> Die neuen Upgrade Parameter angewendet.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor dem Auslösen einer <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ändert die Upgrade-Parameter, die das Verhalten des aktuellen clusterupgrade beschreiben.</para>
        </summary>
        <returns>
          <para>Das aktuelle clusterupgrade.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeConfigurationAsync (description As ConfigurationUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="description">Enthält: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes
            </param>
        <summary>
            Initiieren Sie ein Upgrade mithilfe einer Konfigurationsdatei für den Cluster.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">Enthält: ClusterConfigPath, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
            Initiieren Sie ein Upgrade mithilfe einer Konfigurationsdatei für den Cluster.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeConfigurationAsync (description As ConfigurationUpgradeDescription, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="description">Enthält: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
            Initiieren Sie ein Upgrade mithilfe einer Konfigurationsdatei für den Cluster.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">Enthält: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
            Initiieren Sie ein Upgrade mithilfe einer Konfigurationsdatei für den Cluster.
            </summary>
        <returns>Aufgabe</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeFabricAsync (System.Fabric.Description.FabricUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeFabricAsync(class System.Fabric.Description.FabricUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeFabricAsync(System.Fabric.Description.FabricUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeFabricAsync (upgradeDescription As FabricUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeFabricAsync : System.Fabric.Description.FabricUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeFabricAsync upgradeDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.FabricUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para>Die Beschreibung des Upgrades.</para>
        </param>
        <summary>
          <para>Der Service Fabric-Upgrades.</para>
        </summary>
        <returns>
          <para>Die aktualisierten Service Fabric.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeFabricAsync (System.Fabric.Description.FabricUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeFabricAsync(class System.Fabric.Description.FabricUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeFabricAsync(System.Fabric.Description.FabricUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeFabricAsync : System.Fabric.Description.FabricUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeFabricAsync (upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.FabricUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para>Die Beschreibung des Upgrades.</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Aktualisiert die Fabric-Dienst mithilfe des angegebenen Timeout und ein Abbruchtoken.</para>
        </summary>
        <returns>
          <para>Die aktualisierten Service Fabric.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>