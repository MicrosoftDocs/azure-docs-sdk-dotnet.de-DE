<Type Name="FabricClient+ApplicationManagementClient" FullName="System.Fabric.FabricClient+ApplicationManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ApplicationManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ApplicationManagementClient = class" />
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
      <para>Stellt die Funktionalität zum Verwalten von Service Fabric-Anwendungen bereit.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore)" />
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
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll. In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird. In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore". Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />. 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para>Der vollständige Pfad für das Anwendungspaket für die Quelle.</para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para>Der relative Pfad für das Ziel in den Imagespeicher besitzen. Dieser Pfad ist relativ zum Stammverzeichnis in den imagespeicher besitzen erstellt und als Ziel verwendet wird, für die Anwendung Paket kopieren.</para>
        </param>
        <summary>
          <para>Lädt ein Anwendungspaket in den Imagespeicher besitzen als Vorbereitung für die Bereitstellung eines neuen Anwendungstyp hoch.</para>
        </summary>
        <remarks>
          <para>Das Timeout des Vorgangs wird standardmäßig auf 30 Minuten für systemeigenes Image Store, und es ist kein Timeout-Kapazität für XStore und Dateifreigabe. Kann auch sollten Sie richtige Timeoutwert angeben, in der Funktion überladen von Operatoren<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" /></para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Auf der Image Store ist eine erforderliche Datei nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String, timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string * TimeSpan -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore, timeout)" />
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
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll. In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird. In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore". Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />. 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para>Der vollständige Pfad für das Anwendungspaket für die Quelle.</para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para>Der relative Pfad für das Ziel in den Imagespeicher besitzen. Dieser Pfad ist relativ zum Stammverzeichnis in den imagespeicher besitzen erstellt und als Ziel verwendet wird, für die Anwendung Paket kopieren.</para>
        </param>
        <param name="timeout">
          <para>Das Timeout der Anwendung Paket Kopiervorgang</para>
        </param>
        <summary>
          <para>Lädt ein Anwendungspaket in den Imagespeicher besitzen als Vorbereitung für die Bereitstellung eines neuen Anwendungstyp hoch.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Auf der Image Store ist eine erforderliche Datei nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, System.Fabric.IImageStoreProgressHandler progressHandler, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, class System.Fabric.IImageStoreProgressHandler progressHandler, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.Fabric.IImageStoreProgressHandler,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String, progressHandler As IImageStoreProgressHandler, timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string * System.Fabric.IImageStoreProgressHandler * TimeSpan -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore, progressHandler, timeout)" />
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
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="progressHandler" Type="System.Fabric.IImageStoreProgressHandler" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll. In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird. In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore". Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />. 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para>Der vollständige Pfad für das Anwendungspaket für die Quelle.</para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para>Der relative Pfad für das Ziel in den Imagespeicher besitzen. Dieser Pfad ist relativ zum Stammverzeichnis in den imagespeicher besitzen erstellt und als Ziel verwendet wird, für die Anwendung Paket kopieren.</para>
        </param>
        <param name="progressHandler">
          <para>Der Status-Handler zum Abrufen von Statusinformationen Echtzeit</para>
        </param>
        <param name="timeout">
          <para>Das Timeout der Anwendung Paket Kopiervorgang</para>
        </param>
        <summary>
          <para>Lädt ein Anwendungspaket in den Imagespeicher besitzen als Vorbereitung für die Bereitstellung eines neuen Anwendungstyp hoch.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Auf der Image Store ist eine erforderliche Datei nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateApplicationAsync (System.Fabric.Description.ApplicationDescription applicationDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateApplicationAsync(class System.Fabric.Description.ApplicationDescription applicationDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateApplicationAsync : System.Fabric.Description.ApplicationDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.CreateApplicationAsync applicationDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationDescription" Type="System.Fabric.Description.ApplicationDescription" />
      </Parameters>
      <Docs>
        <param name="applicationDescription">
          <para>Die Beschreibung der Anwendung.</para>
        </param>
        <summary>
          <para>Erstellt und die jeweilige Service Fabric-Anwendung instanziiert.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: Der angeforderte Anwendungstyp wurde noch nicht bereitgestellt wurde.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Auf der Image Store ist eine erforderliche Datei nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                Die angegebene Kapazität Anwendungsparameter sind falsch. Verweisen auf <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> und <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> für die korrekte Angabe der Kapazität Anwendungsparameter.
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateApplicationAsync (System.Fabric.Description.ApplicationDescription applicationDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateApplicationAsync(class System.Fabric.Description.ApplicationDescription applicationDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateApplicationAsync : System.Fabric.Description.ApplicationDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.CreateApplicationAsync (applicationDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationDescription" Type="System.Fabric.Description.ApplicationDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationDescription">
          <para>Die Beschreibung der Anwendung.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das CancellationToken, das beobachten von der Vorgang. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt und die jeweilige Service Fabric-Anwendung instanziiert.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf dem ImageStore gefunden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: Der angeforderte Anwendungstyp wurde noch nicht bereitgestellt wurde.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Auf der Image Store ist eine erforderliche Datei nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                Die angegebene Kapazität Anwendungsparameter sind falsch. Verweisen auf <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> und <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> für die korrekte Angabe der Kapazität Anwendungsparameter.
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : System.Fabric.Description.DeleteApplicationDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync deleteApplicationDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteApplicationDescription" Type="System.Fabric.Description.DeleteApplicationDescription" />
      </Parameters>
      <Docs>
        <param name="deleteApplicationDescription">
          <para>Die Beschreibung der Anwendung gelöscht werden soll.</para>
        </param>
        <summary>
          <para>Löscht die Anwendungsinstanz aus dem Cluster, und löscht alle Dienste, die an die Anwendung gehören.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</para>
          <para>Ein Aufruf erzwungene löschen kann, dass eine erzwungene laufende normalen löschen konvertieren.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert. </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteApplicationAsync (applicationName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use overload taking DeleteApplicationDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI des Instanznamens Anwendung.</para>
        </param>
        <summary>
          <para>Löscht die Anwendungsinstanz aus dem Cluster, und löscht alle Dienste, die an die Anwendung gehören.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert. </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : System.Fabric.Description.DeleteApplicationDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync (deleteApplicationDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteApplicationDescription" Type="System.Fabric.Description.DeleteApplicationDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteApplicationDescription">
          <para>Die Beschreibung der Anwendung gelöscht werden soll.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, die diesen Vorgang vor der Rückgabe System.TimeoutException fortgesetzt werden kann.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Löscht die Anwendungsinstanz aus dem Cluster, und löscht alle Dienste, die an die Anwendung gehören.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</para>
          <para>Ein Aufruf erzwungene löschen kann, dass eine erzwungene laufende normalen löschen konvertieren.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert. </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use overload taking DeleteApplicationDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI des Instanznamens Anwendung.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, die diesen Vorgang vor der Rückgabe System.TimeoutException fortgesetzt werden kann.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Löscht die Anwendungsinstanz aus dem Cluster, und löscht alle Dienste, die an die Anwendung gehören.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert. </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeployServicePackageToNode">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeployServicePackageToNode (string applicationTypeName, string applicationTypeVersion, string serviceManifestName, System.Fabric.PackageSharingPolicyList sharingPolicies, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeployServicePackageToNode(string applicationTypeName, string applicationTypeVersion, string serviceManifestName, class System.Fabric.PackageSharingPolicyList sharingPolicies, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeployServicePackageToNode(System.String,System.String,System.String,System.Fabric.PackageSharingPolicyList,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeployServicePackageToNode : string * string * string * System.Fabric.PackageSharingPolicyList * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeployServicePackageToNode (applicationTypeName, applicationTypeVersion, serviceManifestName, sharingPolicies, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="sharingPolicies" Type="System.Fabric.PackageSharingPolicyList" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>ApplicationTypeName zugeordneten Dienstmanifest heruntergeladen werden</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Version des Anwendungstyp für </para>
        </param>
        <param name="serviceManifestName">
          <para>Name des dienstmanifests, deren Pakete heruntergeladen werden müssen</para>
        </param>
        <param name="sharingPolicies">
          <para>Freigaberichtlinie für Pakete, die für freigegebene Ordner kopiert werden müssen, die darstellt</para>
        </param>
        <param name="nodeName">
          <para>Der Name des Knotens, in denen Pakete heruntergeladen werden müssen.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe: System.TimeoutException</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" />, die der Vorgang beobachtet wird. Sie kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll</para>
        </param>
        <summary>
          <para>Downloads Pakete Dienstmanifest zum Imagecache auf den angegebenen Knoten zugeordnet. </para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetApplicationManifestAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetApplicationManifestAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationManifestAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationManifestAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationManifestAsync : string * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="applicationManagementClient.GetApplicationManifestAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Typname wie im Anwendungsmanifest angegeben.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die Version entsprechend den Angaben im Anwendungsmanifest.</para>
        </param>
        <summary>
          <para>Ruft den Inhalt von einem bereitgestellten Anwendungsmanifest im Cluster gespeichert.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht den unformatierten XML-Zeichenfolgeninhalt des Anwendungsmanifests.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound">
          <para>Die angeforderte Anwendungstyp und-Version wurde nicht bereitgestellt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetApplicationManifestAsync (string applicationTypeName, string applicationTypeVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetApplicationManifestAsync(string applicationTypeName, string applicationTypeVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationManifestAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationManifestAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="applicationManagementClient.GetApplicationManifestAsync (applicationTypeName, applicationTypeVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Typname wie im Anwendungsmanifest angegeben.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die Version entsprechend den Angaben im Anwendungsmanifest.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft den Inhalt von einem bereitgestellten Anwendungsmanifest im Cluster gespeichert.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht den unformatierten XML-Zeichenfolgeninhalt des Anwendungsmanifests.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound">
          <para>Die angeforderte Anwendungstyp und-Version wurde nicht bereitgestellt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationUpgradeProgressAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationUpgradeProgressAsync (applicationName As Uri) As Task(Of ApplicationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationUpgradeProgressAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;" Usage="applicationManagementClient.GetApplicationUpgradeProgressAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI des Instanznamens Anwendung.</para>
        </param>
        <summary>
          <para>Ruft den upgradeverlauf des zur angegebenen Instanz ab.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht den upgradeverlauf des angegebenen Anwendungsinstanz.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationUpgradeProgressAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationUpgradeProgressAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;" Usage="applicationManagementClient.GetApplicationUpgradeProgressAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI des Instanznamens Anwendung.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft den upgradeverlauf des zur angegebenen Instanz ab.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht den upgradeverlauf des angegebenen Anwendungsinstanz.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextApplicationUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync (System.Fabric.ApplicationUpgradeProgress upgradeProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync(class System.Fabric.ApplicationUpgradeProgress upgradeProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function MoveNextApplicationUpgradeDomainAsync (upgradeProgress As ApplicationUpgradeProgress) As Task" />
      <MemberSignature Language="F#" Value="member this.MoveNextApplicationUpgradeDomainAsync : System.Fabric.ApplicationUpgradeProgress -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.MoveNextApplicationUpgradeDomainAsync upgradeProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para>– Der Verlauf des Upgrades der Anwendungsinstanz von Interesse sind. Dies bietet Informationen über die nächste upgradedomäne aktualisiert werden.</para>
        </param>
        <summary>
          <para>Weist die Service Fabric Anwendungsinstanz in die nächste upgradedomäne aktualisiert.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Service Fabric würde nur auf die nächste upgradedomäne verschieben, wenn er die upgradedomäne abgeschlossen wurde, die sie zurzeit aktualisiert wird. Das heißt, <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" /> Eigenschaft sollte sein ausstehender vor dem Aufrufen dieser Methode.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextApplicationUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync (System.Fabric.ApplicationUpgradeProgress upgradeProgress, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync(class System.Fabric.ApplicationUpgradeProgress upgradeProgress, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveNextApplicationUpgradeDomainAsync : System.Fabric.ApplicationUpgradeProgress * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.MoveNextApplicationUpgradeDomainAsync (upgradeProgress, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para>Der Verlauf des Upgrades der Anwendungsinstanz von Interesse sind. Dies bietet Informationen über die nächste upgradedomäne aktualisiert werden.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Weist das Upgrade mit der Anwendungsinstanz in der nächsten upgradedomäne fortgesetzt.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Service Fabric würde nur auf die nächste upgradedomäne verschieben, wenn er die upgradedomäne abgeschlossen wurde, die sie zurzeit aktualisiert wird. Das heißt, <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" /> Eigenschaft sollte sein ausstehender vor dem Aufrufen dieser Methode.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (System.Fabric.Description.ProvisionApplicationTypeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(class System.Fabric.Description.ProvisionApplicationTypeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionApplicationAsync (description As ProvisionApplicationTypeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : System.Fabric.Description.ProvisionApplicationTypeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ProvisionApplicationTypeDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>Beschreibung für die Anforderung bereitstellen.</para>
        </param>
        <summary>
          <para>Bereitstellen oder einen Anwendungstyp mit dem Cluster zu registrieren.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Dies ist obligatorisch, bevor eine Instanz der Anwendung erstellt werden kann.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: Der Anwendungstyp wurde bereits bereitgestellt wurde</para>
        </exception>
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
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionApplicationAsync (applicationPackagePathInImageStore As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : string -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync applicationPackagePathInImageStore" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationPackagePathInImageStore">
          <para>Der relative Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</para>
        </param>
        <summary>
          <para>Stellt einen Service Fabric-Anwendungstyp mit dem Cluster bereit oder registriert einen Service Fabric-Anwendungstyp mit dem Cluster.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Dies ist obligatorisch, bevor eine Instanz der Anwendung erstellt werden kann.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: Der Anwendungstyp wurde bereits bereitgestellt wurde</para>
        </exception>
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
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (System.Fabric.Description.ProvisionApplicationTypeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(class System.Fabric.Description.ProvisionApplicationTypeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : System.Fabric.Description.ProvisionApplicationTypeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ProvisionApplicationTypeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>Beschreibung für die Anforderung bereitstellen.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Bereitstellen oder einen Anwendungstyp mit dem Cluster zu registrieren.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Dies ist obligatorisch, bevor eine Instanz der Anwendung erstellt werden kann.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: Der Anwendungstyp wurde bereits bereitgestellt wurde</para>
        </exception>
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
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (string applicationPackagePathInImageStore, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(string applicationPackagePathInImageStore, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync (applicationPackagePathInImageStore, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationPackagePathInImageStore">
          <para>Der relative Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Bereitstellen oder einen Anwendungstyp mit dem Cluster zu registrieren.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Dies ist obligatorisch, bevor eine Instanz der Anwendung erstellt werden kann.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: Der Anwendungstyp wurde bereits bereitgestellt wurde</para>
        </exception>
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
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveApplicationPackage">
      <MemberSignature Language="C#" Value="public void RemoveApplicationPackage (string imageStoreConnectionString, string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveApplicationPackage(string imageStoreConnectionString, string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RemoveApplicationPackage(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveApplicationPackage (imageStoreConnectionString As String, applicationPackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveApplicationPackage : string * string -&gt; unit" Usage="applicationManagementClient.RemoveApplicationPackage (imageStoreConnectionString, applicationPackagePathInImageStore)" />
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
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para>Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll. In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird. In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore". Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />. 
            </para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para>Der relative Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</para>
        </param>
        <summary>
          <para>Löscht ein Anwendungspaket aus den Imagespeicher besitzen.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf dem ImageStore.</para>
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
    <Member MemberName="RollbackApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackApplicationUpgradeAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackApplicationUpgradeAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RollbackApplicationUpgradeAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RollbackApplicationUpgradeAsync (applicationName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.RollbackApplicationUpgradeAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.RollbackApplicationUpgradeAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Name der Anwendung</para>
        </param>
        <summary>
          <para>Startet die Aktualisierung der aktuellen Anwendung wird ein Rollback ausgeführt.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: Es ist keine ausstehende Upgrade für die angegebene Anwendung, ein Rollback aus.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RollbackApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackApplicationUpgradeAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackApplicationUpgradeAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RollbackApplicationUpgradeAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RollbackApplicationUpgradeAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.RollbackApplicationUpgradeAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Name der Anwendung</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Startet die Aktualisierung der aktuellen Anwendung ein Rollback</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (System.Fabric.Description.UnprovisionApplicationTypeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(class System.Fabric.Description.UnprovisionApplicationTypeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionApplicationAsync (description As UnprovisionApplicationTypeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : System.Fabric.Description.UnprovisionApplicationTypeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.UnprovisionApplicationTypeDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>Beschreibt die Parameter für den Vorgang für das Aufheben der Bereitstellung.</para>
        </param>
        <summary>
          <para>Hebt die Registrierung und einen Service Fabric-Anwendungstyp aus dem Cluster entfernt.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Diese Methode kann nur aufgerufen werden, wenn alle Anwendungsinstanz des Anwendungstyps gelöscht wurde. Sobald die Registrierung des Anwendungstyps aufgehoben ist, kann keine neue Anwendungsinstanz mehr für diesen bestimmten Anwendungstyp erstellt werden.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: Die Anwendung vom Typ wird von einer oder mehreren Anwendungen verwendet. </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionApplicationAsync (applicationTypeName As String, applicationTypeVersion As String) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Name des Anwendungstyps.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die Version des Anwendungstyps.</para>
        </param>
        <summary>
          <para>Hebt die Registrierung und einen Service Fabric-Anwendungstyp aus dem Cluster entfernt.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Diese Methode kann nur aufgerufen werden, wenn alle Anwendungsinstanz des Anwendungstyps gelöscht wurde. Sobald die Registrierung des Anwendungstyps aufgehoben ist, kann keine neue Anwendungsinstanz mehr für diesen bestimmten Anwendungstyp erstellt werden.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: Die Anwendung vom Typ wird von einer oder mehreren Anwendungen verwendet. </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (System.Fabric.Description.UnprovisionApplicationTypeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(class System.Fabric.Description.UnprovisionApplicationTypeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : System.Fabric.Description.UnprovisionApplicationTypeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.UnprovisionApplicationTypeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>Beschreibt die Parameter für den Vorgang für das Aufheben der Bereitstellung.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Hebt die Registrierung und einen Service Fabric-Anwendungstyp aus dem Cluster entfernt.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Diese Methode kann nur aufgerufen werden, wenn alle Anwendungsinstanz des Anwendungstyps gelöscht wurde. Sobald die Registrierung des Anwendungstyps aufgehoben ist, kann keine neue Anwendungsinstanz mehr für diesen bestimmten Anwendungstyp erstellt werden.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: Die Anwendung vom Typ wird von einer oder mehreren Anwendungen verwendet. </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (string applicationTypeName, string applicationTypeVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(string applicationTypeName, string applicationTypeVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (applicationTypeName, applicationTypeVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Name des Anwendungstyps.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die Version des Anwendungstyps.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Hebt die Registrierung und einen Service Fabric-Anwendungstyp aus dem Cluster entfernt.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Diese Methode kann nur aufgerufen werden, wenn alle Anwendungsinstanz des Anwendungstyps gelöscht wurde. Sobald die Registrierung des Anwendungstyps aufgehoben ist, kann keine neue Anwendungsinstanz mehr für diesen bestimmten Anwendungstyp erstellt werden.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: Die Anwendung vom Typ wird von einer oder mehreren Anwendungen verwendet. </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationAsync (System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationAsync(class System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationAsync : System.Fabric.Description.ApplicationUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationAsync applicationUpdateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationUpdateDescription" Type="System.Fabric.Description.ApplicationUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="applicationUpdateDescription">Beschreibung der Anwendung aktualisieren.</param>
        <summary>
            Eine Service Fabric-Anwendung aktualisiert.
            </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: Eine andere Anwendungsupdate wird bereits ausgeführt.
                </para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                Die Anwendung aktualisieren von Parametern angegeben sind falsch. Verweisen auf <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> und <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" /> für die korrekte Angabe der Kapazität Anwendungsparameter.
                </para>
          <para>
                Es ist möglich, diese Parameter in <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> gültig sind, aber in Kombination mit vorhandenen Anwendungsparameter Kapazität erzeugen sie eine ungültige Kombination. Z. B. <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" /> auf einen Wert, der höher als die, die im angegebenen <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> wann die Anwendung erstellt wurde.
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationAsync (System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationAsync(class System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationAsync : System.Fabric.Description.ApplicationUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationAsync (applicationUpdateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationUpdateDescription" Type="System.Fabric.Description.ApplicationUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationUpdateDescription">Beschreibung der Anwendung aktualisieren.</param>
        <param name="timeout">Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</param>
        <param name="cancellationToken">Das CancellationToken, das beobachten von der Vorgang.
            Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</param>
        <summary>
            Eine Service Fabric-Anwendung aktualisiert.
            </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: Eine andere Anwendungsupdate wird bereits ausgeführt.
                </para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                Die Anwendung aktualisieren von Parametern angegeben sind falsch. Verweisen auf <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> und <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" /> für die korrekte Angabe der Kapazität Anwendungsparameter.
                </para>
          <para>
                Es ist möglich, diese Parameter in <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> gültig sind, aber in Kombination mit vorhandenen Anwendungsparameter Kapazität erzeugen sie eine ungültige Kombination. Z. B. <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" /> auf einen Wert, der höher als die, die im angegebenen <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> wann die Anwendung erstellt wurde.
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationUpgradeAsync (System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationUpgradeAsync(class System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateApplicationUpgradeAsync (updateDescription As ApplicationUpgradeUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationUpgradeAsync : System.Fabric.Description.ApplicationUpgradeUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationUpgradeAsync updateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ApplicationUpgradeUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para>Beschreibung des zu ändernden Parameter. Nicht angegeben, Parameter bleiben unverändert bleiben sollen, und ihren aktuellen Wert in der Aktualisierung beibehalten wird.</para>
        </param>
        <summary>
          <para>Ändert das Upgrade ein Upgrade der ausstehenden-Parameter.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: Es ist keine ausstehende Anwendungsupgrades zu ändern.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationUpgradeAsync (System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationUpgradeAsync(class System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationUpgradeAsync : System.Fabric.Description.ApplicationUpgradeUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationUpgradeAsync (updateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ApplicationUpgradeUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para>Beschreibung des zu ändernden Parameter. Nicht angegeben, Parameter bleiben unverändert bleiben sollen, und ihren aktuellen Wert in der Aktualisierung beibehalten wird.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Token, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ändert das Upgrade ein Upgrade der ausstehenden-Parameter.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: Es ist keine ausstehende Anwendungsupgrades zu ändern.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeApplicationAsync (System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeApplicationAsync(class System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpgradeApplicationAsync(System.Fabric.Description.ApplicationUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeApplicationAsync (upgradeDescription As ApplicationUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeApplicationAsync : System.Fabric.Description.ApplicationUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpgradeApplicationAsync upgradeDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.ApplicationUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para>Die Beschreibung der Upgraderichtlinie und die Anwendung zu aktualisieren.</para>
        </param>
        <summary>
          <para>Führt ein Upgrade auf eine Instanz der Anwendung an.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Das Upgrade ist in Bezug auf die bereitgestellten Manifeste ungültig. </para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: Der Anwendungstyp ist nicht vorhanden. </para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung ist bereits auf die angeforderte Version aktualisiert wird.</para>
        </exception>
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
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeApplicationAsync (System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeApplicationAsync(class System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpgradeApplicationAsync(System.Fabric.Description.ApplicationUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeApplicationAsync : System.Fabric.Description.ApplicationUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpgradeApplicationAsync (upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.ApplicationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para>Die Beschreibung der Aktualisierung Richtlinie und die Anwendung aktualisiert werden.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Token, das beobachten von der Vorgang. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Führt ein Upgrade auf eine Instanz der Anwendung an.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Das Upgrade ist in Bezug auf die bereitgestellten Manifeste ungültig. </para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: Der Anwendungstyp ist nicht vorhanden. </para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung ist bereits auf die angeforderte Version aktualisiert wird.</para>
        </exception>
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
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>