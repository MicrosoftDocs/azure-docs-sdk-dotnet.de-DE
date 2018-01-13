<Type Name="FabricClient+HealthClient" FullName="System.Fabric.FabricClient+HealthClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.HealthClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/HealthClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.HealthClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.HealthClient" />
  <TypeSignature Language="F#" Value="type FabricClient.HealthClient = class" />
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
      <para>Stellt Funktionen bereit, führen Sie die Integrität verwandte Vorgänge, z. B. den Status Bericht und der Abfrage.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (System.Fabric.Description.ApplicationHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Fabric.Description.ApplicationHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (queryDescription As ApplicationHealthQueryDescription) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : System.Fabric.Description.ApplicationHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ApplicationHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> Instanz um die Abfrage zum Abrufen der Anwendungsintegrität zu beschreiben.</param>
        <summary>
          <para>Ruft Sie die Integrität der angegebenen Service Fabric-Anwendung mithilfe der angegebenen abfragebeschreibung asynchron ab.</para>
        </summary>
        <returns>
          <para>Die Integrität der angegebenen Service Fabric-Anwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (applicationName As Uri) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <summary>
          <para>Ruft asynchron die Integrität der angegebenen Service Fabric-Anwendung ab.</para>
        </summary>
        <returns>
          <para>Die Integrität der angegebenen Service Fabric-Anwendung.</para>
        </returns>
        <remarks>
          <para>Im folgenden Beispiel wird die Integrität einer Anwendung.</para>
          <code language="c#">Öffentliche statische Bool GetApplicationHealth(string clusterConnection) {ApplicationHealth ApplicationHealth; URI-Parameter "ApplicationName" = neue Uri("fabric:/myapp/todo");
            
                Mit dem Cluster verbinden.
                FabricClient FabricClient = neue FabricClient(clusterConnection);
            
                Abrufen der Anwendungsintegrität.
                Wiederholen Sie den {ApplicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);
            
                Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);
                
                "false" zurückgeben; }
                    
                Anzeigen von Informationen der Integrität.
                Console.WriteLine ("Abrufen der Anwendungsintegrität:"); Console.WriteLine ("Anwendung {0}: \ {1\}", applicationHealth.ApplicationName, applicationHealth.AggregatedHealthState);
                
                    Liste der Integritätsstatus der bereitgestellten Anwendung.
            Console.WriteLine ("bereitgestellten Anwendungen:"); IList&lt;DeployedApplicationHealthState&gt; DeployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; Foreach (DeployedApplicationHealthState DeployedAppHealthState in DeployedAppHealthStateList) {Console.WriteLine ("Anwendung:" + deployedAppHealthState.ApplicationName); Console.WriteLine ("aggregierte Integritätsstatus:" + deployedAppHealthState.AggregatedHealthState); Console.WriteLine ("Node Name:" + deployedAppHealthState.NodeName);}
                    
            Liste der Integritätsstatus der bereitgestellten Dienste.
            Console.WriteLine ("Dienstintegritätszustände:"); IList&lt;ServiceHealthState&gt; DeployedSvcsHealthStateList = applicationHealth.ServiceHealthStates; Foreach (ServiceHealthState ServiceHealthState in DeployedSvcsHealthStateList) {Console.WriteLine ("Service {0}: \{1 \} ", serviceHealthState.ServiceName, serviceHealthState.AggregatedHealthState); }
                    
                Überblick über die Integritätsdienst-Ereignisse.
            Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = applicationHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}
                
                Console.WriteLine(); "true" zurückgeben; }
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationHealthAsync (applicationName As Uri, healthPolicy As ApplicationHealthPolicy) As Task(Of ApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="healthPolicy">Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> Instanz verwendet, um die Anwendung auszuwerten.</param>
        <summary>
          <para>Ruft asynchron die Integrität der angegebenen Service Fabric-Anwendung, die mit dem Anwendungs-URI und der Integritätsrichtlinie ab.</para>
        </summary>
        <returns>
          <para>Die Integritätsberichte der angegebenen Service Fabric-Anwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (System.Fabric.Description.ApplicationHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Fabric.Description.ApplicationHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : System.Fabric.Description.ApplicationHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ApplicationHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> Instanz um die Abfrage zum Abrufen der Anwendungsintegrität zu beschreiben.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität der angegebenen Service Fabric-Anwendung, die mit dem angegebenen abfrageeingabe, Timeout und Abbruch Ruft asynchron ab token.</para>
        </summary>
        <returns>
          <para>Die Integritätsberichte der angegebenen Service Fabric-Anwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität der angegebenen Service Fabric-Anwendung, die mit dem angegebenen Anwendungs-URI, Timeout und ein Abbruch Ruft asynchron ab token.</para>
        </summary>
        <returns>
          <para>Die Integritätsberichte der angegebenen Service Fabric-Anwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync (Uri applicationName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ApplicationHealth&gt; GetApplicationHealthAsync(class System.Uri applicationName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;" Usage="healthClient.GetApplicationHealthAsync (applicationName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Anwendungszustand auszuwerten.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab der Integrität der angegebenen Service Fabric-Anwendung mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integritätsberichte der angegebenen Service Fabric-Anwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync () As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft asynchron die Integrität des Service Fabric-Cluster ab.</para>
        </summary>
        <returns>
          <para>Die Integrität von Service Fabric-Cluster.</para>
        </returns>
        <remarks>
          <para>Im folgenden Beispiel wird die Integrität des Clusters.</para>
          <code language="c#">Öffentliche statische Bool GetClusterHealth(string clusterConnection) {ClusterHealth ClusterHealth;
            
                Mit dem Cluster verbinden.
            FabricClient FabricClient = neue FabricClient(clusterConnection);
                
                Rufen Sie den Clusterzustand an.
            Wiederholen Sie den {ClusterHealth = fabricClient.HealthManager.GetClusterHealthAsync(). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);
                
                Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);
                
                    "false" zurückgeben; }
                
                Anzeigen des Integritätsstatus des Clusters an.
                Console.WriteLine ("Cluster-Integrität:"); Console.WriteLine ("aggregierte Integritätsstatus:" + clusterHealth.AggregatedHealthState); Console.WriteLine();
                    
            Anzeigen des Integritätsstatus der Anwendung auf dem Cluster an.
                    Console.WriteLine ("Anwendungsintegritätszustände:"); IList&lt;ApplicationHealthState&gt; ApplicationHealthStateList = clusterHealth.ApplicationHealthStates; Foreach (ApplicationHealthState ApplicationHealthState in ApplicationHealthStateList) {Console.WriteLine ("    Anwendung {0}: \ {1\} ", applicationHealthState.ApplicationName, applicationHealthState.AggregatedHealthState); }
            
            Anzeigen von Knotenintegritätszustände, auf dem Cluster.
                    Console.WriteLine ("Knotenintegritätszustände:"); IList&lt;NodeHealthState&gt; NodeHealthStateList = clusterHealth.NodeHealthStates; Foreach (NodeHealthState NodeHealthState in NodeHealthStateList) {Console.WriteLine ("Node Name:" + nodeHealthState.NodeName); Console.WriteLine ("aggregierte Integritätsstatus:" + nodeHealthState.AggregatedHealthState);}
                
            Integritätsereignisse anzeigen
                Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEventList = clusterHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEventList) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}
                
                Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = clusterHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}
                
            "true" zurückgeben; }
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Description.ClusterHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Description.ClusterHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync (queryDescription As ClusterHealthQueryDescription) As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Description.ClusterHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage, die definiert, wie Integritätsrichtlinien, Abfrageparameter filtert usw.</param>
        <summary>
          <para>Ruft Sie die Integrität des Service Fabric-Cluster mit einer Beschreibung der Abfrage asynchron ab.</para>
        </summary>
        <returns>
          <para>Die Integrität von Service Fabric-Cluster.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Health.ClusterHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Health.ClusterHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthAsync (healthPolicy As ClusterHealthPolicy) As Task(Of ClusterHealth)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Health.ClusterHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync healthPolicy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="healthPolicy">Die clusterintegritätsrichtlinie, die zum Auswerten der clusterintegrität verwendet wird.</param>
        <summary>
          <para>Ruft asynchron die Integrität eines Service Fabric-Clusters mithilfe der angegebenen Richtlinie auswerten ab.</para>
        </summary>
        <returns>
          <para>Die Integrität von Service Fabric-Cluster.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität des Service Fabric-Cluster Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität von Service Fabric-Cluster.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Description.ClusterHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Description.ClusterHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Description.ClusterHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage, die Abfrageparameter wie Integritätsrichtlinien definiert filtert usw.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab die Integrität des Service Fabric-Cluster mit einer Beschreibung der Abfrage, ein Timeout und der Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität von Service Fabric-Cluster.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync (System.Fabric.Health.ClusterHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealth&gt; GetClusterHealthAsync(class System.Fabric.Health.ClusterHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Health.ClusterHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthAsync : System.Fabric.Health.ClusterHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;" Usage="healthClient.GetClusterHealthAsync (healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="healthPolicy">Die clusterintegritätsrichtlinie, die zum Auswerten der clusterintegrität verwendet wird.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab die Integrität des Service Fabric-Cluster mithilfe der angegebenen Integritätsrichtlinie, Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität von Service Fabric-Cluster.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthChunkAsync () As Task(Of ClusterHealthChunk)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Integrität eines Service Fabric-Clusters ab.
            </summary>
        <returns>Das Integritätsdienst-Segment, das den Clusterzustand darstellt.</returns>
        <remarks>Der Integritätsstatus für den Cluster, die aggregiert wird basierend auf alle Entitäten im Cluster berechnet.
            Keine untergeordneten Elemente sind in den Ergebnissen enthalten, da keine Filter angegeben werden.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(class System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterHealthChunkAsync (queryDescription As ClusterHealthChunkQueryDescription) As Task(Of ClusterHealthChunk)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : System.Fabric.Description.ClusterHealthChunkQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthChunkQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage, die definiert, wie der integritätsauswertung ausgeführt werden sollen und welche Entitäten beinhalten soll die <see cref="T:System.Fabric.Health.ClusterHealthChunk" />.</param>
        <summary>
            Ruft die Integrität des Service Fabric-Cluster, einschließlich Cluster Entitäten, wie in der Beschreibung der Abfrage angefordert.
            </summary>
        <returns>Das Integritätsdienst-Segment, das den Clusterzustand darstellt.</returns>
        <remarks>Der Integritätsstatus für den Cluster, die aggregiert wird basierend auf alle Entitäten im Cluster berechnet. Nur die untergeordneten Elemente, die die Filter aus der Eingabeabfrage-Beschreibung (sofern vorhanden) zu berücksichtigen sind in den Ergebnissen enthalten.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</param>
        <param name="cancellationToken">Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</param>
        <summary>
            Ruft die Integrität eines Service Fabric-Clusters ab.
            </summary>
        <returns>Das Integritätsdienst-Segment, das den Clusterzustand darstellt.</returns>
        <remarks>Der Integritätsstatus für den Cluster, die aggregiert wird basierend auf alle Entitäten im Cluster berechnet. Keine untergeordneten Elemente sind in den Ergebnissen enthalten, da keine Filter angegeben werden.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterHealthChunkAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync (System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ClusterHealthChunk&gt; GetClusterHealthChunkAsync(class System.Fabric.Description.ClusterHealthChunkQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterHealthChunkAsync : System.Fabric.Description.ClusterHealthChunkQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;" Usage="healthClient.GetClusterHealthChunkAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ClusterHealthChunk&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterHealthChunkQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage, die definiert, wie der integritätsauswertung ausgeführt werden sollen und welche Entitäten beinhalten soll die <see cref="T:System.Fabric.Health.ClusterHealthChunk" />.</param>
        <param name="timeout">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</param>
        <param name="cancellationToken">Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</param>
        <summary>
            Ruft die Integrität des Service Fabric-Cluster, einschließlich Cluster Entitäten, wie in der Beschreibung der Abfrage angefordert.
            </summary>
        <returns>Das Integritätsdienst-Segment, das den Clusterzustand darstellt.</returns>
        <remarks>Der Integritätsstatus für den Cluster, die aggregiert wird basierend auf alle Entitäten im Cluster berechnet. Nur die untergeordneten Elemente, die die Filter aus der Eingabeabfrage-Beschreibung (sofern vorhanden) zu berücksichtigen sind in den Ergebnissen enthalten.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (queryDescription As DeployedApplicationHealthQueryDescription) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : System.Fabric.Description.DeployedApplicationHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <summary>
          <para>Ruft asynchron ab die Integrität einer bereitgestellten Service Fabric-Anwendung auf dem angegebenen Knoten mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (applicationName As Uri, nodeName As String) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="nodeName">
          <para>Der Knotenname, in dem die Service Fabric-Anwendung bereitgestellt wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron den Zustand einer bereitgestellten Service Fabric-Anwendung, auf dem angegebenen Knoten.</para>
        </summary>
        <returns>
          <para>Die Integrität einer bereitgestellten Service Fabric-Anwendung.</para>
        </returns>
        <remarks>
          <para>Im folgenden Beispiel wird die Integrität einer bereitgestellten Anwendung.</para>
          <code language="c#">Öffentliche statische Bool GetDeployedApplicationsHealth(string clusterConnection) {//DeployedApplicationHealth DeployedApplicationHealth; //ApplicationHealth ApplicationHealth; URI-Parameter "ApplicationName" = neue Uri("fabric:/myapp/todo");
            
                Mit dem Cluster verbinden.
                FabricClient FabricClient = neue FabricClient(clusterConnection);
                
            Console.WriteLine ("Anwendungsintegrität bereitgestellt:");
                
                Wiederholen Sie den {/ / bestimmen Sie die Knoten, in dem die Anwendung bereitgestellt wurde.
            ApplicationHealth ApplicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName). Ergebnis.
                
            Rufen Sie die Integrität der bereitgestellten Anwendung für jeden Knoten.
                IList&lt;DeployedApplicationHealthState&gt; DeployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; Foreach (DeployedApplicationHealthState DeployedAppHealthState in DeployedAppHealthStateList) {DeployedApplicationHealth DeployedApplicationHealth = fabricClient.HealthManager.GetDeployedApplicationHealthAsync (Parameter "ApplicationName", deployedAppHealthState.NodeName). Ergebnis.
                
                    Die bereitgestellte Anwendung Integritäts-Informationen für jeden Knoten angezeigt.
                    
            Console.WriteLine ("Anwendung {0}: \ {1\}", deployedApplicationHealth.ApplicationName, deployedApplicationHealth.AggregatedHealthState); Console.WriteLine ("Node Name:" + deployedApplicationHealth.NodeName);
                    
                    Liste der Integritätsstatus der bereitgestellten Anwendung.
                    Console.WriteLine ("bereitgestellten Anwendungen:"); IList&lt;DeployedServicePackageHealthState&gt; DeployedSPHealthStateList = deployedApplicationHealth.DeployedServicePackageHealthStates; Foreach (DeployedServicePackageHealthState DeployedSPHealthState in DeployedSPHealthStateList) {Console.WriteLine ("Anwendung:" + deployedSPHealthState.ApplicationName); Console.WriteLine ("aggregierte Integritätsstatus:" + deployedSPHealthState.AggregatedHealthState); Console.WriteLine ("Node Name:" + deployedSPHealthState.NodeName); Console.WriteLine ("Manifest Dienstname:" + deployedSPHealthState.ServiceManifestName);}
                    
            Überblick über die Integritätsdienst-Ereignisse.
                Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = deployedApplicationHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}
            
            Listen Sie die fehlerhaften auswertungen.
            Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = deployedApplicationHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}
            
            Console.WriteLine(); }} Catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);
            
            Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);
            
            "false" zurückgeben; }
            
            "true" zurückgeben; }
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Fabric.Description.DeployedApplicationHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : System.Fabric.Description.DeployedApplicationHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab die Integrität einer bereitgestellten Service Fabric-Anwendung auf dem angegebenen Knoten mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationHealthAsync (applicationName As Uri, nodeName As String, healthPolicy As ApplicationHealthPolicy) As Task(Of DeployedApplicationHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="nodeName">
          <para>Der Knotenname, in dem die Service Fabric-Anwendung bereitgestellt wird.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <summary>
          <para>Ruft asynchron den Zustand einer bereitgestellten Service Fabric-Anwendung, auf dem angegebenen Knoten.</para>
        </summary>
        <returns>
          <para>Die Integrität einer bereitgestellten Service Fabric-Anwendung.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="nodeName">
          <para>Der Knotenname, in dem die Service Fabric-Anwendung bereitgestellt wird.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab die Integrität einer bereitgestellten Service Fabric-Anwendung auf dem angegebenen Knoten mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync (Uri applicationName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedApplicationHealth&gt; GetDeployedApplicationHealthAsync(class System.Uri applicationName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Uri,System.String,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationHealthAsync : Uri * string * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;" Usage="healthClient.GetDeployedApplicationHealthAsync (applicationName, nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedApplicationHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="nodeName">
          <para>Der Knotenname, in dem die Service Fabric-Anwendung bereitgestellt wird.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab die Integrität einer bereitgestellten Service Fabric-Anwendung auf dem angegebenen Knoten mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (queryDescription As DeployedServicePackageHealthQueryDescription) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : System.Fabric.Description.DeployedServicePackageHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <summary>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Fabric.Description.DeployedServicePackageHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : System.Fabric.Description.DeployedServicePackageHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (applicationName As Uri, serviceManifestName As String, nodeName As String) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="serviceManifestName">
          <para>Der Name des Diensts Manifestdatei für diesen Service Fabric-Dienst.</para>
        </param>
        <param name="nodeName">
          <para>Der Name des Knotens, der für der Service Fabric-Dienst bereitgestellt wurde.</para>
        </param>
        <summary>
          <para>Ruft asynchron die Integrität eines Dienstpakets bereitgestellten Service Fabric ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</para>
        </returns>
        <remarks>
          <para>Im folgenden Beispiel wird die Integrität eines Dienstpakets bereitgestellt.</para>
          <code language="c#">Öffentliche statische Bool GetDeployedServicePackageHealth(string clusterConnection) {DeployedApplicationHealth DeployedApplicationHealth; DeployedServicePackageHealth DeployedServicePackageHealth; ApplicationHealth ApplicationHealth; URI-Parameter "ApplicationName" = neue Uri("fabric:/myapp/todo");
            
                Mit dem Cluster verbinden.
                FabricClient FabricClient = neue FabricClient(clusterConnection);
                
                Console.WriteLine ("Integrität eines Dienstpakets bereitgestellt:");
            
                Wiederholen Sie den {/ / bestimmen Sie die Knoten, in dem die Anwendung bereitgestellt wurde.
                ApplicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName). Ergebnis.
            
                Abgerufen Sie die bereitgestellte dienstpaketintegrität für jeden Knoten werden.
            IList&lt;DeployedApplicationHealthState&gt; DeployedApplicationHealthStateList = applicationHealth.DeployedApplicationHealthStates; Foreach (DeployedApplicationHealthState DeployedApplicationHealthState in DeployedApplicationHealthStateList) {/ / Abrufen der Integrität der bereitgestellten Anwendung, die den Namen des Dienst-Manifests enthält und / / die Namen der Knoten, auf dem der Dienst bereitgestellt wurde.
                DeployedApplicationHealth = fabricClient.HealthManager.GetDeployedApplicationHealthAsync (Parameter "ApplicationName", deployedApplicationHealthState.NodeName). Ergebnis.
                
                    Zurück, wenn dieses leer.
                    Wenn (deployedApplicationHealth.DeployedServicePackageHealthStates.Count == 0) "false"; zurückgeben
            
                    Rufen Sie die Integrität der bereitgestellten Dienst-Paket.
                    DeployedServicePackageHealth = fabricClient.HealthManager.GetDeployedServicePackageHealthAsync (Parameter "ApplicationName", deployedApplicationHealth.DeployedServicePackageHealthStates[0]. ServiceManifestName, deployedApplicationHealthState.NodeName). Ergebnis.
                    
                    Anzeigen der Integrität bereitgestellter Dienst Paketinformationen.
            Console.WriteLine ("Anwendungsname:" + deployedServicePackageHealth.ApplicationName); Console.WriteLine ("Node Name:" + deployedServicePackageHealth.NodeName); Console.WriteLine ("aggregierte Integritätsstatus:" + deployedServicePackageHealth.AggregatedHealthState); Console.WriteLine ("Manifest Dienstname:" + deployedServicePackageHealth.ServiceManifestName);
            
            Überblick über die Integritätsdienst-Ereignisse.
                Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = deployedServicePackageHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}
            
            Listen Sie die fehlerhaften auswertungen.
            Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = deployedServicePackageHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}
                
            Console.WriteLine(); }} Catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);
            
            Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);
                
                "false" zurückgeben; } "true"; zurückgeben }
            </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageHealthAsync (applicationName As Uri, serviceManifestName As String, nodeName As String, healthPolicy As ApplicationHealthPolicy) As Task(Of DeployedServicePackageHealth)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="serviceManifestName">
          <para>Der Name des Diensts Manifestdatei für diesen Service Fabric-Dienst.</para>
        </param>
        <param name="nodeName">
          <para>Der Name des Knotens, der für der Service Fabric-Dienst bereitgestellt wurde.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <summary>
          <para>Ruft asynchron die Integrität eines Dienstpakets bereitgestellten Service Fabric ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="serviceManifestName">
          <para>Der Name des Diensts Manifestdatei für diesen Service Fabric-Dienst.</para>
        </param>
        <param name="nodeName">
          <para>Der Name des Knotens, der für der Service Fabric-Dienst bereitgestellt wurde.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync (Uri applicationName, string serviceManifestName, string nodeName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.DeployedServicePackageHealth&gt; GetDeployedServicePackageHealthAsync(class System.Uri applicationName, string serviceManifestName, string nodeName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Uri,System.String,System.String,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageHealthAsync : Uri * string * string * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;" Usage="healthClient.GetDeployedServicePackageHealthAsync (applicationName, serviceManifestName, nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.DeployedServicePackageHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI der Service Fabric-Anwendung.</para>
        </param>
        <param name="serviceManifestName">
          <para>Der Name des Diensts Manifestdatei für diesen Service Fabric-Dienst.</para>
        </param>
        <param name="nodeName">
          <para>Der Name des Knotens, der für der Service Fabric-Dienst bereitgestellt wurde.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (System.Fabric.Description.NodeHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(class System.Fabric.Description.NodeHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (queryDescription As NodeHealthQueryDescription) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : System.Fabric.Description.NodeHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.NodeHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage, die Parameter wie Integritätsrichtlinie definiert filtert usw.</param>
        <summary>
          <para>Die Integrität eines Service Fabric-Knotens Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Knotens.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (nodeName As String) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Service Fabric-Knoten.</para>
        </param>
        <summary>
          <para>Ruft asynchron die Integrität eines Service Fabric-Knotens ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Knotens.</para>
        </returns>
        <remarks>
          <para>Im folgenden Beispiel wird die Integrität eines Knotens.</para>
          <code language="c#">Öffentliche statische Bool GetNodeHealth(string clusterConnection) {NodeHealth NodeHealth;
            
                Mit dem Cluster verbinden.
            FabricClient FabricClient = neue FabricClient(clusterConnection);
                
                Abrufen der knotenintegrität an.
            Wiederholen Sie den {NodeHealth = fabricClient.HealthManager.GetNodeHealthAsync("Node1"). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);
                
                Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);
                
                    "false" zurückgeben; }
                
                Anzeigen der Integritätsinformationen der Knoten an.
                Console.WriteLine ("Knotenintegrität:"); Console.WriteLine ("Knoten {0}: \ {1\}", nodeHealth.NodeName, nodeHealth.AggregatedHealthState);
                    
            Überblick über die Integritätsdienst-Ereignisse.
                    Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = nodeHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}
            
            Listen Sie die fehlerhaften auswertungen.
                    Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = nodeHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}
                
            Console.WriteLine(); "true" zurückgeben; }
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, System.Fabric.Health.ClusterHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, class System.Fabric.Health.ClusterHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeHealthAsync (nodeName As String, healthPolicy As ClusterHealthPolicy) As Task(Of NodeHealth)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * System.Fabric.Health.ClusterHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Service Fabric-Knoten.</para>
        </param>
        <param name="healthPolicy">Die clusterintegritätsrichtlinie verwendet, um den Zustand des Knotens auszuwerten.</param>
        <summary>
          <para>Ruft asynchron die Integrität eines Service Fabric-Knotens ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Knotens.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (System.Fabric.Description.NodeHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(class System.Fabric.Description.NodeHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : System.Fabric.Description.NodeHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.NodeHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage, die Parameter wie Integritätsrichtlinie definiert filtert usw.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Service Fabric-Knotens Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Knotens.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Service Fabric-Knoten.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Service Fabric-Knotens Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Knotens.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync (string nodeName, System.Fabric.Health.ClusterHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.NodeHealth&gt; GetNodeHealthAsync(string nodeName, class System.Fabric.Health.ClusterHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.String,System.Fabric.Health.ClusterHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeHealthAsync : string * System.Fabric.Health.ClusterHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;" Usage="healthClient.GetNodeHealthAsync (nodeName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.NodeHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Service Fabric-Knoten.</para>
        </param>
        <param name="healthPolicy">Die clusterintegritätsrichtlinie verwendet, um den Zustand des Knotens auszuwerten.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Service Fabric-Knotens Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Knotens.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (System.Fabric.Description.PartitionHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(class System.Fabric.Description.PartitionHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (queryDescription As PartitionHealthQueryDescription) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : System.Fabric.Description.PartitionHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PartitionHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <summary>
          <para>Ruft asynchron ab die Integrität einer Service Fabric-Partition mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität einer Service Fabric-Partition.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (partitionId As Guid) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die ID der Service Fabric-Partition.</para>
        </param>
        <summary>
          <para>Ruft asynchron die Integrität einer Service Fabric-Partition ab.</para>
        </summary>
        <returns>
          <para>Die Integrität einer Service Fabric-Partition.</para>
        </returns>
        <remarks>
          <para>Im folgenden Beispiel wird die Integrität einer Partition.</para>
          <code language="c#">Öffentliche statische Bool GetPartitionHealth(string clusterConnection) {PartitionHealth PartitionHealth;
            
                Mit dem Cluster verbinden.
            FabricClient FabricClient = neue FabricClient(clusterConnection);
                
                Abrufen der partitionsintegrität an.
            Wiederholen Sie den {PartitionHealth = fabricClient.HealthManager.GetPartitionHealthAsync (neue Guid("a7206315-e53b-4d05-b59c-e210caa28893")). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);
                
                Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);
                
                    "false" zurückgeben; }
                
                Anzeigen der Integritätsinformationen der Partition an.
                Console.WriteLine ("Partitions-Integrität:"); Console.WriteLine ("Partitions-ID:" + partitionHealth.PartitionId); Console.WriteLine ("aggregierte Integritätsstatus:" + partitionHealth.AggregatedHealthState);
                    
            Überblick über die Integritätsdienst-Ereignisse.
                    Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = partitionHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}
                        
            Liste der replikatintegritätszustände an.
                    Console.WriteLine ("Replikatintegritätszustände:"); IList&lt;ReplicaHealthState&gt; ReplicaHealthStates = partitionHealth.ReplicaHealthStates; Foreach (ReplicaHealthState ReplicaHealthState in ReplicaHealthStates) {Console.WriteLine ("ID:" + replicaHealthState.Id); Console.WriteLine ("Art:" + replicaHealthState.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + replicaHealthState.AggregatedHealthState); Console.WriteLine ("Partitions-ID:" + replicaHealthState.PartitionId);}
                
            Listen Sie die fehlerhaften auswertungen.
                Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = partitionHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}
                
                Console.WriteLine(); "true" zurückgeben; }
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionHealthAsync (partitionId As Guid, healthPolicy As ApplicationHealthPolicy) As Task(Of PartitionHealth)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die ID der Service Fabric-Partition.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <summary>
          <para>Ruft asynchron die Integrität einer Service Fabric-Partition ab.</para>
        </summary>
        <returns>
          <para>Die Integrität einer Service Fabric-Partition.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (System.Fabric.Description.PartitionHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(class System.Fabric.Description.PartitionHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : System.Fabric.Description.PartitionHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PartitionHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab die Integrität einer Service Fabric-Partition mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität einer Service Fabric-Partition.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die ID der Service Fabric-Partition.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab die Integrität einer Service Fabric-Partition mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität einer Service Fabric-Partition.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync (Guid partitionId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.PartitionHealth&gt; GetPartitionHealthAsync(valuetype System.Guid partitionId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Guid,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionHealthAsync : Guid * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;" Usage="healthClient.GetPartitionHealthAsync (partitionId, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.PartitionHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die ID der Service Fabric-Partition.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab die Integrität einer Service Fabric-Partition mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität einer Service Fabric-Partition.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (System.Fabric.Description.ReplicaHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(class System.Fabric.Description.ReplicaHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (queryDescription As ReplicaHealthQueryDescription) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : System.Fabric.Description.ReplicaHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ReplicaHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <summary>
          <para>Ruft asynchron die Integrität eines Service Fabric-Replikats, die gemäß der Beschreibung der Abfrage ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Replikats.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (partitionId As Guid, replicaId As Long) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die ID der Service Fabric-Partition.</para>
        </param>
        <param name="replicaId">
          <para>Die ID des Service Fabric-Replikats.</para>
        </param>
        <summary>
          <para>Ruft asynchron die Integrität eines Service Fabric-Replikats ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Replikats.</para>
        </returns>
        <remarks>
          <para>Im folgenden Beispiel wird die Integrität eines Replikats an.</para>
          <code language="c#">Öffentliche statische Bool GetReplicaHealth(string clusterConnection) {ReplicaHealth ReplicaHealth;
            
                Mit dem Cluster verbinden.
            FabricClient FabricClient = neue FabricClient(clusterConnection);
                
                Abrufen der replikatintegrität an.
            Wiederholen Sie den {ReplicaHealth = fabricClient.HealthManager.GetReplicaHealthAsync (neue Guid("a7206315-e53b-4d05-b59c-e210caa28893"), 130538257146083818). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);
                
                Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);
                
                    "false" zurückgeben; }
            
                Console.WriteLine ("Replikatintegrität:"); Console.WriteLine ("ID:" + replicaHealth.Id); Console.WriteLine ("aggregierte Integritätsstatus:" + replicaHealth.AggregatedHealthState); Console.WriteLine ("Art:" + replicaHealth.Kind); Console.WriteLine ("Partitions-ID:" + replicaHealth.PartitionId);
                
                Überblick über die Integritätsdienst-Ereignisse.
                    Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = replicaHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}
            
                    Listen Sie die fehlerhaften auswertungen.
            Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = replicaHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}
            
                    Console.WriteLine(); "true" zurückgeben; }
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (System.Fabric.Description.ReplicaHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(class System.Fabric.Description.ReplicaHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Fabric.Description.ReplicaHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : System.Fabric.Description.ReplicaHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ReplicaHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Service Fabric-Replikats Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Replikats.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaHealthAsync (partitionId As Guid, replicaId As Long, healthPolicy As ApplicationHealthPolicy) As Task(Of ReplicaHealth)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die ID der Service Fabric-Partition.</para>
        </param>
        <param name="replicaId">
          <para>Die ID des Service Fabric-Replikats.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <summary>
          <para>Ruft asynchron die Integrität eines Service Fabric-Replikats ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Replikats.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die ID der Service Fabric-Partition.</para>
        </param>
        <param name="replicaId">
          <para>Die ID des Service Fabric-Replikats.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Service Fabric-Replikats Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Replikats.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync (Guid partitionId, long replicaId, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ReplicaHealth&gt; GetReplicaHealthAsync(valuetype System.Guid partitionId, int64 replicaId, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetReplicaHealthAsync(System.Guid,System.Int64,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaHealthAsync : Guid * int64 * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;" Usage="healthClient.GetReplicaHealthAsync (partitionId, replicaId, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ReplicaHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die ID der Service Fabric-Partition.</para>
        </param>
        <param name="replicaId">
          <para>Die ID des Service Fabric-Replikats.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Die Integrität eines Service Fabric-Replikats Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Replikats.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (System.Fabric.Description.ServiceHealthQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Fabric.Description.ServiceHealthQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (queryDescription As ServiceHealthQueryDescription) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : System.Fabric.Description.ServiceHealthQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ServiceHealthQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <summary>
          <para>Ruft asynchron ab der Integrität eines Service Fabric-Dienstes mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Dienstes.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (serviceName As Uri) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Service Fabric-Dienstes.</para>
        </param>
        <summary>
          <para>Ruft asynchron die Integrität eines Service Fabric-Dienstes ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Dienstes.</para>
        </returns>
        <remarks>
          <para>Im folgenden Beispiel wird die Integrität eines Diensts.</para>
          <code language="c#">Öffentliche statische Bool GetServiceHealth(string clusterConnection) {ServiceHealth ServiceHealth; URI-ServiceName = neue Uri("fabric:/myapp/todo/svc1");
            
                Mit dem Cluster verbinden.
                FabricClient FabricClient = neue FabricClient(clusterConnection);
            
                Rufen Sie die dienstintegrität.
                Wiederholen Sie den {ServiceHealth = fabricClient.HealthManager.GetServiceHealthAsync(serviceName). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);
            
                Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);
                
                "false" zurückgeben; }
                    
                Console.WriteLine ("Health Service:"); Console.WriteLine ("Service {0}: \ {1\}", serviceHealth.ServiceName, serviceHealth.AggregatedHealthState);
                
                Liste der Zustände.
                    Console.WriteLine ("Partition Zustände:"); IList&lt;PartitionHealthState&gt; PartitionHealthStates = serviceHealth.PartitionHealthStates; Foreach (PartitionHealthState PartitionHealthState in PartitionHealthStates) {Console.WriteLine ("aggregierten Integritätsstatus: "+ partitionHealthState.AggregatedHealthState); Console.WriteLine ("Partitions-ID:" + partitionHealthState.PartitionId);}
            
                    Überblick über die Integritätsdienst-Ereignisse.
            Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = serviceHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}
            
                    Listen Sie die fehlerhaften auswertungen.
                Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = serviceHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}
            
                Console.WriteLine(); "true" zurückgeben; }
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="serviceName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceHealthAsync (serviceName As Uri, healthPolicy As ApplicationHealthPolicy) As Task(Of ServiceHealth)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, healthPolicy)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Service Fabric-Dienstes.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung zur Bewertung der Integrität des Diensts.</param>
        <summary>
          <para>Ruft asynchron die Integrität eines Service Fabric-Dienstes ab.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Dienstes.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="serviceName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (System.Fabric.Description.ServiceHealthQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Fabric.Description.ServiceHealthQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : System.Fabric.Description.ServiceHealthQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ServiceHealthQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">Die Beschreibung der Abfrage.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab der Integrität eines Service Fabric-Dienstes mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Dienstes.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Service Fabric-Dienstes.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab der Integrität eines Service Fabric-Dienstes mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Dienstes.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="serviceName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceHealthAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync (Uri serviceName, System.Fabric.Health.ApplicationHealthPolicy healthPolicy, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Health.ServiceHealth&gt; GetServiceHealthAsync(class System.Uri serviceName, class System.Fabric.Health.ApplicationHealthPolicy healthPolicy, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Uri,System.Fabric.Health.ApplicationHealthPolicy,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceHealthAsync : Uri * System.Fabric.Health.ApplicationHealthPolicy * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;" Usage="healthClient.GetServiceHealthAsync (serviceName, healthPolicy, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Health.ServiceHealth&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="healthPolicy" Type="System.Fabric.Health.ApplicationHealthPolicy" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Service Fabric-Dienstes.</para>
        </param>
        <param name="healthPolicy">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.
            Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron ab der Integrität eines Service Fabric-Dienstes mit dem angegebenen Timeout und Abbruch token.</para>
        </summary>
        <returns>
          <para>Die Integrität eines Service Fabric-Dienstes.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="serviceName" /> ist kein gültiger Service Fabric Name.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportHealth">
      <MemberSignature Language="C#" Value="public void ReportHealth (System.Fabric.Health.HealthReport healthReport);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReportHealth(class System.Fabric.Health.HealthReport healthReport) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />
      <MemberSignature Language="F#" Value="member this.ReportHealth : System.Fabric.Health.HealthReport -&gt; unit" Usage="healthClient.ReportHealth healthReport" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthReport" Type="System.Fabric.Health.HealthReport" />
      </Parameters>
      <Docs>
        <param name="healthReport">
          <para>Das <see cref="T:System.Fabric.Health.HealthReport" />, das gesendet werden soll.</para>
        </param>
        <summary>
          <para>Integrität für eine Entität Service Fabric gemeldet.</para>
        </summary>
        <remarks>
          <para>
             Bei ein Cluster geschützt wird, benötigt der Client Integrität Administrator eine Zugriffsberechtigung für die Berichte senden kann.
             Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">Herstellen einer Verbindung zu einem Cluster mit den APIs FabricClient</see>.
            </para>
          <para>
             Weitere Informationen zur Integrität Berichterstattung finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric-Integritätsüberwachung</see>.
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportHealth">
      <MemberSignature Language="C#" Value="public void ReportHealth (System.Fabric.Health.HealthReport healthReport, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReportHealth(class System.Fabric.Health.HealthReport healthReport, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="member this.ReportHealth : System.Fabric.Health.HealthReport * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="healthClient.ReportHealth (healthReport, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthReport" Type="System.Fabric.Health.HealthReport" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthReport">
          <para>Das <see cref="T:System.Fabric.Health.HealthReport" />, das gesendet werden soll.</para>
        </param>
        <param name="sendOptions">
          <para>Die <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> ab, der steuert, wie der Bericht gesendet wird.</para>
        </param>
        <summary>
          <para>Integrität der Berichte auf einem Service Fabric-Entität und übergibt senden Optionen zum Steuern, wie der Bericht gesendet wird.</para>
        </summary>
        <remarks>
          <para>
             Bei ein Cluster geschützt wird, benötigt der Client Integrität Administrator eine Zugriffsberechtigung für die Berichte senden kann.
             Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">Herstellen einer Verbindung mit einem Cluster mithilfe der FabricClient-APIs.</see></para>
          <para>
             Weitere Informationen zur Integrität Berichterstattung finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric-Integritätsüberwachung</see>.
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Durch eine der folgenden Ursachen:</para>
          <para>E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>