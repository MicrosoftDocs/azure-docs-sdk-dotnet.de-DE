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
      <para><span data-ttu-id="0d439-101">Stellt Funktionen bereit, führen Sie die Integrität verwandte Vorgänge, z. B. den Status Bericht und der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-101">Provides functionality to perform health related operations, like report and query health.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-102">Die <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> Instanz um die Abfrage zum Abrufen der Anwendungsintegrität zu beschreiben.</span><span class="sxs-lookup"><span data-stu-id="0d439-102">The <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> instance to describe the query to get application health.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-103">Ruft Sie die Integrität der angegebenen Service Fabric-Anwendung mithilfe der angegebenen abfragebeschreibung asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-103">Asynchronously gets the health of the specified Service Fabric application by using the specified query description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-104">Die Integrität der angegebenen Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-104">The health of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-105">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-105">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-106">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-106">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-107">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-107">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-108">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-108">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-109">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-109">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-110">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-110">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-111"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-111"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-112">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-112">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-113"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-113"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-114"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-114"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-115"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-115"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-116"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-116"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-117"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-117"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-118"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-118"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-119"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-119"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-120"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-120"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-121"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-121"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-122"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-122"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-123"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-123"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-124"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-124"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-125">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-125">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-126"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-126"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-127">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-127">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-128">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-128">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-129">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-129">The URI of the Service Fabric application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-130">Ruft asynchron die Integrität der angegebenen Service Fabric-Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-130">Asynchronously gets the health of the specified Service Fabric application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-131">Die Integrität der angegebenen Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-131">The health of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="0d439-132">Im folgenden Beispiel wird die Integrität einer Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-132">The following example gets the health of an application.</span></span></para>
          <code language="c#"><span data-ttu-id="0d439-133">Öffentliche statische Bool GetApplicationHealth(string clusterConnection) {ApplicationHealth ApplicationHealth; URI-Parameter "ApplicationName" = neue Uri("fabric:/myapp/todo");</span><span class="sxs-lookup"><span data-stu-id="0d439-133">public static bool GetApplicationHealth(string clusterConnection) { ApplicationHealth applicationHealth; Uri applicationName = new Uri("fabric:/myapp/todo");</span></span>
            
                <span data-ttu-id="0d439-134">Mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="0d439-134">// Connect to the cluster.</span></span>
                <span data-ttu-id="0d439-135">FabricClient FabricClient = neue FabricClient(clusterConnection);</span><span class="sxs-lookup"><span data-stu-id="0d439-135">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
            
                <span data-ttu-id="0d439-136">Abrufen der Anwendungsintegrität.</span><span class="sxs-lookup"><span data-stu-id="0d439-136">// Get the application health.</span></span>
                <span data-ttu-id="0d439-137">Wiederholen Sie den {ApplicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-137">try { applicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName).Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
            
                <span data-ttu-id="0d439-138">Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-138">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                <span data-ttu-id="0d439-139">"false" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-139">return false; }</span></span>
                    
                <span data-ttu-id="0d439-140">Anzeigen von Informationen der Integrität.</span><span class="sxs-lookup"><span data-stu-id="0d439-140">// Display the application health information.</span></span>
                <span data-ttu-id="0d439-141">Console.WriteLine ("Abrufen der Anwendungsintegrität:"); Console.WriteLine ("Anwendung {0}: \ {1\}", applicationHealth.ApplicationName, applicationHealth.AggregatedHealthState);</span><span class="sxs-lookup"><span data-stu-id="0d439-141">Console.WriteLine("Get Application Health:"); Console.WriteLine("  Application {0}: {1}", applicationHealth.ApplicationName, applicationHealth.AggregatedHealthState);</span></span>
                
                    <span data-ttu-id="0d439-142">Liste der Integritätsstatus der bereitgestellten Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-142">// List the deployed application health states.</span></span>
            <span data-ttu-id="0d439-143">Console.WriteLine ("bereitgestellten Anwendungen:"); IList&lt;DeployedApplicationHealthState&gt; DeployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; Foreach (DeployedApplicationHealthState DeployedAppHealthState in DeployedAppHealthStateList) {Console.WriteLine ("Anwendung:" + deployedAppHealthState.ApplicationName); Console.WriteLine ("aggregierte Integritätsstatus:" + deployedAppHealthState.AggregatedHealthState); Console.WriteLine ("Node Name:" + deployedAppHealthState.NodeName);}</span><span class="sxs-lookup"><span data-stu-id="0d439-143">Console.WriteLine("    Deployed applications:"); IList&lt;DeployedApplicationHealthState&gt; deployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedAppHealthState in deployedAppHealthStateList) { Console.WriteLine("      Application: " + deployedAppHealthState.ApplicationName); Console.WriteLine("        Aggregated Health State: " + deployedAppHealthState.AggregatedHealthState); Console.WriteLine("        Node Name: " + deployedAppHealthState.NodeName); }</span></span>
                    
            <span data-ttu-id="0d439-144">Liste der Integritätsstatus der bereitgestellten Dienste.</span><span class="sxs-lookup"><span data-stu-id="0d439-144">// List the deployed services health states.</span></span>
            <span data-ttu-id="0d439-145">Console.WriteLine ("Dienstintegritätszustände:"); IList&lt;ServiceHealthState&gt; DeployedSvcsHealthStateList = applicationHealth.ServiceHealthStates; Foreach (ServiceHealthState ServiceHealthState in DeployedSvcsHealthStateList) {Console.WriteLine ("Service {0}: \{1 \} ", serviceHealthState.ServiceName, serviceHealthState.AggregatedHealthState); }</span><span class="sxs-lookup"><span data-stu-id="0d439-145">Console.WriteLine("    Service Health States:"); IList&lt;ServiceHealthState&gt; deployedSvcsHealthStateList = applicationHealth.ServiceHealthStates; foreach (ServiceHealthState serviceHealthState in deployedSvcsHealthStateList) { Console.WriteLine("      Service {0}: {1}", serviceHealthState.ServiceName, serviceHealthState.AggregatedHealthState); }</span></span>
                    
                <span data-ttu-id="0d439-146">Überblick über die Integritätsdienst-Ereignisse.</span><span class="sxs-lookup"><span data-stu-id="0d439-146">// List the health events.</span></span>
            <span data-ttu-id="0d439-147">Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = applicationHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="0d439-147">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = applicationHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
                
                <span data-ttu-id="0d439-148">Console.WriteLine(); "true" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-148">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-149">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-149">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-150">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-150">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-151">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-151">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-152">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-152">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-153"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-153"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-154">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-154">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-155"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-155"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-156"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-156"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-157"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-157"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-158"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-158"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-159"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-159"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-160"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-160"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-161"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-161"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-162"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-162"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-163"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-163"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-164"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-164"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-165"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-165"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-166"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-166"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-167">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-167">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-168"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-168"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-169">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-169">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-170">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-170">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-171">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-171">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-172">Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> Instanz verwendet, um die Anwendung auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-172">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> instance used to evaluate the application.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-173">Ruft asynchron die Integrität der angegebenen Service Fabric-Anwendung, die mit dem Anwendungs-URI und der Integritätsrichtlinie ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-173">Asynchronously gets the health of the specified Service Fabric application using the application URI and the health policy.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-174">Die Integritätsberichte der angegebenen Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-174">The health reports of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-175">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-175">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-176">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-176">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-177">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-177">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-178">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-178">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-179">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-179">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-180">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-180">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-181"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-181"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-182">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-182">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-183"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-183"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-184"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-184"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-185"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-185"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-186"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-186"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-187"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-187"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-188"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-188"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-189"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-189"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-190"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-190"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-191"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-191"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-192"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-192"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-193"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-193"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-194"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-194"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-195">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-195">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-196"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-196"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-197">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-197">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-198">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-198">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-199">Die <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> Instanz um die Abfrage zum Abrufen der Anwendungsintegrität zu beschreiben.</span><span class="sxs-lookup"><span data-stu-id="0d439-199">The <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> instance to describe the query to get application health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-200">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-200">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-201">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-201">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-202">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-202">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-203">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-203">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-204">Die Integrität der angegebenen Service Fabric-Anwendung, die mit dem angegebenen abfrageeingabe, Timeout und Abbruch Ruft asynchron ab token.</span><span class="sxs-lookup"><span data-stu-id="0d439-204">Asynchronously gets the health of the specified Service Fabric application using the specified query input, timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-205">Die Integritätsberichte der angegebenen Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-205">The health reports of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-206">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-206">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-207">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-207">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-208">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-208">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-209">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-209">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-210">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-210">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-211">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-211">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-212"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-212"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-213">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-213">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-214"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-214"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-215"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-215"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-216"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-216"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-217"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-217"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-218"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-218"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-219"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-219"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-220"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-220"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-221"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-221"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-222"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-222"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-223"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-223"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-224"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-224"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-225"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-225"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-226">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-226">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-227"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-227"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-228">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-228">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-229">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-229">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-230">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-230">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-231">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-231">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-232">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-232">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-233">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-233">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-234">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-234">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-235">Die Integrität der angegebenen Service Fabric-Anwendung, die mit dem angegebenen Anwendungs-URI, Timeout und ein Abbruch Ruft asynchron ab token.</span><span class="sxs-lookup"><span data-stu-id="0d439-235">Asynchronously gets the health of the specified Service Fabric application using the specified application URI, timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-236">Die Integritätsberichte der angegebenen Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-236">The health reports of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-237">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-237">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-238">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-238">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-239">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-239">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-240">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-240">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-241">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-241">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-242">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-242">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-243"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-243"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-244">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-244">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-245"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-245"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-246"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-246"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-247"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-247"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-248"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-248"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-249"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-249"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-250"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-250"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-251"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-251"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-252"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-252"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-253"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-253"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-254"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-254"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-255"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-255"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-256"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-256"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-257">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-257">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-258"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-258"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-259">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-259">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-260">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-260">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-261">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-261">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-262">Die Integritätsrichtlinie für die Anwendung verwendet, um den Anwendungszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-262">The application health policy used to evaluate the application health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-263">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-263">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-264">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-264">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-265">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-265">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-266">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-266">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-267">Ruft asynchron ab der Integrität der angegebenen Service Fabric-Anwendung mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-267">Asynchronously gets the health of the specified Service Fabric application by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-268">Die Integritätsberichte der angegebenen Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-268">The health reports of the specified Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-269">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-269">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-270">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-270">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-271">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-271">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-272">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-272">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-273">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-273">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-274">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-274">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-275"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-275"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-276">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-276">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-277"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-277"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-278"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-278"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-279"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-279"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-280"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-280"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-281"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-281"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-282"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-282"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-283"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-283"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-284"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-284"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-285"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-285"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-286"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-286"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-287"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-287"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-288"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-288"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-289">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-289">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-290"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-290"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-291">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-291">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-292">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-292">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-293">Ruft asynchron die Integrität des Service Fabric-Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-293">Asynchronously gets the health of a Service Fabric cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-294">Die Integrität von Service Fabric-Cluster.</span><span class="sxs-lookup"><span data-stu-id="0d439-294">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="0d439-295">Im folgenden Beispiel wird die Integrität des Clusters.</span><span class="sxs-lookup"><span data-stu-id="0d439-295">The following example gets the health of the cluster.</span></span></para>
          <code language="c#"><span data-ttu-id="0d439-296">Öffentliche statische Bool GetClusterHealth(string clusterConnection) {ClusterHealth ClusterHealth;</span><span class="sxs-lookup"><span data-stu-id="0d439-296">public static bool GetClusterHealth(string clusterConnection) { ClusterHealth clusterHealth;</span></span>
            
                <span data-ttu-id="0d439-297">Mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="0d439-297">// Connect to the cluster.</span></span>
            <span data-ttu-id="0d439-298">FabricClient FabricClient = neue FabricClient(clusterConnection);</span><span class="sxs-lookup"><span data-stu-id="0d439-298">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="0d439-299">Rufen Sie den Clusterzustand an.</span><span class="sxs-lookup"><span data-stu-id="0d439-299">// Get the cluster health.</span></span>
            <span data-ttu-id="0d439-300">Wiederholen Sie den {ClusterHealth = fabricClient.HealthManager.GetClusterHealthAsync(). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-300">try { clusterHealth = fabricClient.HealthManager.GetClusterHealthAsync().Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
                
                <span data-ttu-id="0d439-301">Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-301">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                    <span data-ttu-id="0d439-302">"false" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-302">return false; }</span></span>
                
                <span data-ttu-id="0d439-303">Anzeigen des Integritätsstatus des Clusters an.</span><span class="sxs-lookup"><span data-stu-id="0d439-303">// Display the cluster health state.</span></span>
                <span data-ttu-id="0d439-304">Console.WriteLine ("Cluster-Integrität:"); Console.WriteLine ("aggregierte Integritätsstatus:" + clusterHealth.AggregatedHealthState); Console.WriteLine();</span><span class="sxs-lookup"><span data-stu-id="0d439-304">Console.WriteLine("Cluster Health:"); Console.WriteLine("  Aggregated Health State: " + clusterHealth.AggregatedHealthState); Console.WriteLine();</span></span>
                    
            <span data-ttu-id="0d439-305">Anzeigen des Integritätsstatus der Anwendung auf dem Cluster an.</span><span class="sxs-lookup"><span data-stu-id="0d439-305">// Display the application health states on the cluster.</span></span>
                    <span data-ttu-id="0d439-306">Console.WriteLine ("Anwendungsintegritätszustände:"); IList&lt;ApplicationHealthState&gt; ApplicationHealthStateList = clusterHealth.ApplicationHealthStates; Foreach (ApplicationHealthState ApplicationHealthState in ApplicationHealthStateList) {Console.WriteLine ("    Anwendung {0}: \ {1\} ", applicationHealthState.ApplicationName, applicationHealthState.AggregatedHealthState); }</span><span class="sxs-lookup"><span data-stu-id="0d439-306">Console.WriteLine("  Application Health States:"); IList&lt;ApplicationHealthState&gt; applicationHealthStateList = clusterHealth.ApplicationHealthStates; foreach(ApplicationHealthState applicationHealthState in applicationHealthStateList) { Console.WriteLine("    Application {0}: {1}", applicationHealthState.ApplicationName, applicationHealthState.AggregatedHealthState); }</span></span>
            
            <span data-ttu-id="0d439-307">Anzeigen von Knotenintegritätszustände, auf dem Cluster.</span><span class="sxs-lookup"><span data-stu-id="0d439-307">// Display Node Health States on the cluster.</span></span>
                    <span data-ttu-id="0d439-308">Console.WriteLine ("Knotenintegritätszustände:"); IList&lt;NodeHealthState&gt; NodeHealthStateList = clusterHealth.NodeHealthStates; Foreach (NodeHealthState NodeHealthState in NodeHealthStateList) {Console.WriteLine ("Node Name:" + nodeHealthState.NodeName); Console.WriteLine ("aggregierte Integritätsstatus:" + nodeHealthState.AggregatedHealthState);}</span><span class="sxs-lookup"><span data-stu-id="0d439-308">Console.WriteLine("  Node Health States:"); IList&lt;NodeHealthState&gt; nodeHealthStateList = clusterHealth.NodeHealthStates; foreach (NodeHealthState nodeHealthState in nodeHealthStateList) { Console.WriteLine("    Node Name: " + nodeHealthState.NodeName); Console.WriteLine("      Aggregated Health State: " + nodeHealthState.AggregatedHealthState); }</span></span>
                
            <span data-ttu-id="0d439-309">Integritätsereignisse anzeigen</span><span class="sxs-lookup"><span data-stu-id="0d439-309">// Display Health Events.</span></span>
                <span data-ttu-id="0d439-310">Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEventList = clusterHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEventList) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="0d439-310">Console.WriteLine("  Health Events:"); IList&lt;HealthEvent&gt; healthEventList = clusterHealth.HealthEvents; foreach(HealthEvent healthEvent in healthEventList) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
                
                <span data-ttu-id="0d439-311">Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = clusterHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="0d439-311">Console.WriteLine("  Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = clusterHealth.UnhealthyEvaluations; foreach(HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("    Kind: " + healthEvaluation.Kind); Console.WriteLine("      Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("      Description: " + healthEvaluation.Description); }</span></span>
                
            <span data-ttu-id="0d439-312">"true" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-312">return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-313">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-313">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-314">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-314">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-315">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-315">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-316">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-316">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-317">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-317">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-318">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-318">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-319"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-319"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-320">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-320">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-321"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-321"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-322"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-322"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-323"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-323"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-324"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-324"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-325"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-325"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-326"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-326"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-327"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-327"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-328"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-328"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-329"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-329"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-330"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-330"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-331"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-331"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-332">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-332">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-333"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-333"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-334">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-334">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-335">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-335">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-336">Die Beschreibung der Abfrage, die definiert, wie Integritätsrichtlinien, Abfrageparameter filtert usw.</span><span class="sxs-lookup"><span data-stu-id="0d439-336">The query description that defines query parameters like health policies, filters etc.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-337">Ruft Sie die Integrität des Service Fabric-Cluster mit einer Beschreibung der Abfrage asynchron ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-337">Asynchronously gets the health of a Service Fabric cluster by using a query description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-338">Die Integrität von Service Fabric-Cluster.</span><span class="sxs-lookup"><span data-stu-id="0d439-338">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-339">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-339">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-340">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-340">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-341">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-341">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-342">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-342">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-343">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-343">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-344">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-344">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-345"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-345"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-346">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-346">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-347"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-347"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-348"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-348"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-349"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-349"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-350"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-350"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-351"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-351"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-352"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-352"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-353"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-353"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-354"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-354"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-355"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-355"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-356"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-356"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-357"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-357"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-358">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-358">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-359"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-359"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-360">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-360">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-361">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-361">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="healthPolicy"><span data-ttu-id="0d439-362">Die clusterintegritätsrichtlinie, die zum Auswerten der clusterintegrität verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-362">The cluster health policy used to evaluate cluster health.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-363">Ruft asynchron die Integrität eines Service Fabric-Clusters mithilfe der angegebenen Richtlinie auswerten ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-363">Asynchronously gets the health of a Service Fabric cluster, evaluating it using the specified policy.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-364">Die Integrität von Service Fabric-Cluster.</span><span class="sxs-lookup"><span data-stu-id="0d439-364">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-365">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-365">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-366">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-366">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-367">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-367">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-368">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-368">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-369">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-369">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-370">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-370">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-371"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-371"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-372">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-372">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-373"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-373"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-374"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-374"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-375"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-375"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-376"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-376"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-377"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-377"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-378"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-378"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-379"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-379"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-380"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-380"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-381"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-381"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-382"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-382"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-383"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-383"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-384">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-384">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-385"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-385"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-386">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-386">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-387">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-387">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-388">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-388">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-389">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-389">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-390">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-390">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="0d439-391">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-391">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-392">Die Integrität des Service Fabric-Cluster Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-392">Asynchronously gets the health of a Service Fabric cluster by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-393">Die Integrität von Service Fabric-Cluster.</span><span class="sxs-lookup"><span data-stu-id="0d439-393">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-394">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-394">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-395">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-395">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-396">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-396">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-397">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-397">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-398">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-398">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-399">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-399">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-400"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-400"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-401">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-401">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-402"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-402"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-403"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-403"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-404"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-404"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-405"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-405"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-406"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-406"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-407"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-407"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-408"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-408"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-409"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-409"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-410"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-410"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-411"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-411"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-412"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-412"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-413">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-413">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-414"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-414"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-415">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-415">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-416">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-416">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-417">Die Beschreibung der Abfrage, die Abfrageparameter wie Integritätsrichtlinien definiert filtert usw.</span><span class="sxs-lookup"><span data-stu-id="0d439-417">The query description that defined query parameters like health policies, filters etc.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-418">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-418">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-419">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-419">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-420">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-420">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="0d439-421">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-421">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-422">Ruft asynchron ab die Integrität des Service Fabric-Cluster mit einer Beschreibung der Abfrage, ein Timeout und der Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-422">Asynchronously gets the health of a Service Fabric cluster by using a query description, a timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-423">Die Integrität von Service Fabric-Cluster.</span><span class="sxs-lookup"><span data-stu-id="0d439-423">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-424">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-424">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-425">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-425">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-426">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-426">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-427">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-427">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-428">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-428">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-429">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-429">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-430"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-430"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-431">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-431">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-432"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-432"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-433"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-433"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-434"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-434"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-435"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-435"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-436"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-436"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-437"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-437"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-438"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-438"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-439"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-439"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-440"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-440"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-441"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-441"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-442"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-442"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-443">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-443">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-444"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-444"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-445">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-445">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-446">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-446">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="healthPolicy"><span data-ttu-id="0d439-447">Die clusterintegritätsrichtlinie, die zum Auswerten der clusterintegrität verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-447">The cluster health policy used to evaluate cluster health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-448">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-448">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-449">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-449">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-450">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-450">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="0d439-451">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-451">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-452">Ruft asynchron ab die Integrität des Service Fabric-Cluster mithilfe der angegebenen Integritätsrichtlinie, Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-452">Asynchronously gets the health of a Service Fabric cluster by using the specified health policy, timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-453">Die Integrität von Service Fabric-Cluster.</span><span class="sxs-lookup"><span data-stu-id="0d439-453">The health of a Service Fabric cluster.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-454">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-454">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-455">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-455">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-456">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-456">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-457">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-457">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-458">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-458">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-459">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-459">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-460"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-460"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-461">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-461">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-462"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-462"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-463"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-463"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-464"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-464"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-465"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-465"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-466"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-466"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-467"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-467"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-468"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-468"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-469"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-469"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-470"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-470"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-471"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-471"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-472"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-472"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-473">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-473">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-474"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-474"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-475">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-475">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-476">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-476">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
            <span data-ttu-id="0d439-477">Ruft die Integrität eines Service Fabric-Clusters ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-477">Gets the health of a Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="0d439-478">Das Integritätsdienst-Segment, das den Clusterzustand darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-478">The health chunk representing the cluster health.</span></span></returns>
        <remarks><span data-ttu-id="0d439-479">Der Integritätsstatus für den Cluster, die aggregiert wird basierend auf alle Entitäten im Cluster berechnet.</span><span class="sxs-lookup"><span data-stu-id="0d439-479">The cluster aggregated health state is computed based on all entities in the cluster.</span></span>
            <span data-ttu-id="0d439-480">Keine untergeordneten Elemente sind in den Ergebnissen enthalten, da keine Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="0d439-480">No children are included in the results, because no filters are specified.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="0d439-481">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-481">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="0d439-482">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-482">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-483">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-483">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-484"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-484"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
                <span data-ttu-id="0d439-485">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="0d439-485">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-486">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-486">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-487"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-487"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-488">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-488">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-489">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-489">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-490">Die Beschreibung der Abfrage, die definiert, wie der integritätsauswertung ausgeführt werden sollen und welche Entitäten beinhalten soll die <see cref="T:System.Fabric.Health.ClusterHealthChunk" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-490">The query description that defines how health evaluation should be performed and what entities should be included in the <see cref="T:System.Fabric.Health.ClusterHealthChunk" />.</span></span></param>
        <summary>
            <span data-ttu-id="0d439-491">Ruft die Integrität des Service Fabric-Cluster, einschließlich Cluster Entitäten, wie in der Beschreibung der Abfrage angefordert.</span><span class="sxs-lookup"><span data-stu-id="0d439-491">Gets the health of a Service Fabric cluster, including cluster entities as requested in the query description.</span></span>
            </summary>
        <returns><span data-ttu-id="0d439-492">Das Integritätsdienst-Segment, das den Clusterzustand darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-492">The health chunk representing the cluster health.</span></span></returns>
        <remarks><span data-ttu-id="0d439-493">Der Integritätsstatus für den Cluster, die aggregiert wird basierend auf alle Entitäten im Cluster berechnet.</span><span class="sxs-lookup"><span data-stu-id="0d439-493">The cluster aggregated health state is computed based on all entities in the cluster.</span></span> <span data-ttu-id="0d439-494">Nur die untergeordneten Elemente, die die Filter aus der Eingabeabfrage-Beschreibung (sofern vorhanden) zu berücksichtigen sind in den Ergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="0d439-494">Only the children that respect the filters from the input query description (if any) are included in the results.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="0d439-495">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-495">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="0d439-496">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-496">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-497">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-497">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-498"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-498"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
                <span data-ttu-id="0d439-499">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="0d439-499">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-500">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-500">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-501">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-501">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-502">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-502">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-503">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-503">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-504"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-504"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-505">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-505">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-506">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-506">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="timeout"><span data-ttu-id="0d439-507">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-507">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="0d439-508">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-508">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-509">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-509">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="0d439-510">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-510">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></param>
        <summary>
            <span data-ttu-id="0d439-511">Ruft die Integrität eines Service Fabric-Clusters ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-511">Gets the health of a Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="0d439-512">Das Integritätsdienst-Segment, das den Clusterzustand darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-512">The health chunk representing the cluster health.</span></span></returns>
        <remarks><span data-ttu-id="0d439-513">Der Integritätsstatus für den Cluster, die aggregiert wird basierend auf alle Entitäten im Cluster berechnet.</span><span class="sxs-lookup"><span data-stu-id="0d439-513">The cluster aggregated health state is computed based on all entities in the cluster.</span></span> <span data-ttu-id="0d439-514">Keine untergeordneten Elemente sind in den Ergebnissen enthalten, da keine Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="0d439-514">No children are included in the results, because no filters are specified.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="0d439-515">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-515">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="0d439-516">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-516">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-517">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-517">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-518"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-518"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
                <span data-ttu-id="0d439-519">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="0d439-519">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-520">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-520">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-521"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-521"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-522">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-522">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-523">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-523">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-524">Die Beschreibung der Abfrage, die definiert, wie der integritätsauswertung ausgeführt werden sollen und welche Entitäten beinhalten soll die <see cref="T:System.Fabric.Health.ClusterHealthChunk" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-524">The query description that defines how health evaluation should be performed and what entities should be included in the <see cref="T:System.Fabric.Health.ClusterHealthChunk" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="0d439-525">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-525">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="0d439-526">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-526">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-527">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-527">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="0d439-528">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-528">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></param>
        <summary>
            <span data-ttu-id="0d439-529">Ruft die Integrität des Service Fabric-Cluster, einschließlich Cluster Entitäten, wie in der Beschreibung der Abfrage angefordert.</span><span class="sxs-lookup"><span data-stu-id="0d439-529">Gets the health of a Service Fabric cluster, including cluster entities as requested in the query description.</span></span>
            </summary>
        <returns><span data-ttu-id="0d439-530">Das Integritätsdienst-Segment, das den Clusterzustand darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-530">The health chunk representing the cluster health.</span></span></returns>
        <remarks><span data-ttu-id="0d439-531">Der Integritätsstatus für den Cluster, die aggregiert wird basierend auf alle Entitäten im Cluster berechnet.</span><span class="sxs-lookup"><span data-stu-id="0d439-531">The cluster aggregated health state is computed based on all entities in the cluster.</span></span> <span data-ttu-id="0d439-532">Nur die untergeordneten Elemente, die die Filter aus der Eingabeabfrage-Beschreibung (sofern vorhanden) zu berücksichtigen sind in den Ergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="0d439-532">Only the children that respect the filters from the input query description (if any) are included in the results.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="0d439-533">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-533">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="0d439-534">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-534">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-535">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-535">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-536"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-536"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
                <span data-ttu-id="0d439-537">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="0d439-537">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-538">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-538">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-539">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-539">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-540">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-540">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-541">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-541">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-542"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-542"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-543">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-543">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-544">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-544">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-545">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-545">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-546">Ruft asynchron ab die Integrität einer bereitgestellten Service Fabric-Anwendung auf dem angegebenen Knoten mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-546">Asynchronously gets the health of a deployed Service Fabric application on the specified node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-547">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-547">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-548">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-548">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-549">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-549">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-550">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-550">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-551">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-551">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-552">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-552">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-553">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-553">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-554"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-554"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-555">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-555">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-556"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-556"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-558"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-558"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-559"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-559"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-560"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-560"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-561"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-561"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-562"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-562"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-563"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-563"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-564"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-564"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-565"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-565"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-566"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-566"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-567"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-567"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-568">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-568">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-569"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-569"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-570">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-570">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-571">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-571">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-572">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-572">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="0d439-573">Der Knotenname, in dem die Service Fabric-Anwendung bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-573">The node name where the Service Fabric application is deployed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-574">Ruft asynchron den Zustand einer bereitgestellten Service Fabric-Anwendung, auf dem angegebenen Knoten.</span><span class="sxs-lookup"><span data-stu-id="0d439-574">Asynchronously gets the health of a deployed Service Fabric application on the specified node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-575">Die Integrität einer bereitgestellten Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-575">The health of a deployed Service Fabric application.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="0d439-576">Im folgenden Beispiel wird die Integrität einer bereitgestellten Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-576">The following example gets the health of a deployed application.</span></span></para>
          <code language="c#"><span data-ttu-id="0d439-577">Öffentliche statische Bool GetDeployedApplicationsHealth(string clusterConnection) {//DeployedApplicationHealth DeployedApplicationHealth; //ApplicationHealth ApplicationHealth; URI-Parameter "ApplicationName" = neue Uri("fabric:/myapp/todo");</span><span class="sxs-lookup"><span data-stu-id="0d439-577">public static bool GetDeployedApplicationsHealth(string clusterConnection) { //DeployedApplicationHealth deployedApplicationHealth; //ApplicationHealth applicationHealth; Uri applicationName = new Uri("fabric:/myapp/todo");</span></span>
            
                <span data-ttu-id="0d439-578">Mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="0d439-578">// Connect to the cluster.</span></span>
                <span data-ttu-id="0d439-579">FabricClient FabricClient = neue FabricClient(clusterConnection);</span><span class="sxs-lookup"><span data-stu-id="0d439-579">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
            <span data-ttu-id="0d439-580">Console.WriteLine ("Anwendungsintegrität bereitgestellt:");</span><span class="sxs-lookup"><span data-stu-id="0d439-580">Console.WriteLine("Deployed Application Health:");</span></span>
                
                <span data-ttu-id="0d439-581">Wiederholen Sie den {/ / bestimmen Sie die Knoten, in dem die Anwendung bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0d439-581">try { // Determine the nodes where the application has been deployed.</span></span>
            <span data-ttu-id="0d439-582">ApplicationHealth ApplicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName). Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="0d439-582">ApplicationHealth applicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName).Result;</span></span>
                
            <span data-ttu-id="0d439-583">Rufen Sie die Integrität der bereitgestellten Anwendung für jeden Knoten.</span><span class="sxs-lookup"><span data-stu-id="0d439-583">// Get the deployed application health for each node.</span></span>
                <span data-ttu-id="0d439-584">IList&lt;DeployedApplicationHealthState&gt; DeployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; Foreach (DeployedApplicationHealthState DeployedAppHealthState in DeployedAppHealthStateList) {DeployedApplicationHealth DeployedApplicationHealth = fabricClient.HealthManager.GetDeployedApplicationHealthAsync (Parameter "ApplicationName", deployedAppHealthState.NodeName). Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="0d439-584">IList&lt;DeployedApplicationHealthState&gt; deployedAppHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedAppHealthState in deployedAppHealthStateList) { DeployedApplicationHealth deployedApplicationHealth = fabricClient.HealthManager.GetDeployedApplicationHealthAsync(applicationName, deployedAppHealthState.NodeName).Result;</span></span>
                
                    <span data-ttu-id="0d439-585">Die bereitgestellte Anwendung Integritäts-Informationen für jeden Knoten angezeigt.</span><span class="sxs-lookup"><span data-stu-id="0d439-585">// Display the deployed application health information for each node.</span></span>
                    
            <span data-ttu-id="0d439-586">Console.WriteLine ("Anwendung {0}: \ {1\}", deployedApplicationHealth.ApplicationName, deployedApplicationHealth.AggregatedHealthState); Console.WriteLine ("Node Name:" + deployedApplicationHealth.NodeName);</span><span class="sxs-lookup"><span data-stu-id="0d439-586">Console.WriteLine("  Application {0}: {1}", deployedApplicationHealth.ApplicationName, deployedApplicationHealth.AggregatedHealthState); Console.WriteLine("    Node Name: " + deployedApplicationHealth.NodeName);</span></span>
                    
                    <span data-ttu-id="0d439-587">Liste der Integritätsstatus der bereitgestellten Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-587">// List the deployed application health states.</span></span>
                    <span data-ttu-id="0d439-588">Console.WriteLine ("bereitgestellten Anwendungen:"); IList&lt;DeployedServicePackageHealthState&gt; DeployedSPHealthStateList = deployedApplicationHealth.DeployedServicePackageHealthStates; Foreach (DeployedServicePackageHealthState DeployedSPHealthState in DeployedSPHealthStateList) {Console.WriteLine ("Anwendung:" + deployedSPHealthState.ApplicationName); Console.WriteLine ("aggregierte Integritätsstatus:" + deployedSPHealthState.AggregatedHealthState); Console.WriteLine ("Node Name:" + deployedSPHealthState.NodeName); Console.WriteLine ("Manifest Dienstname:" + deployedSPHealthState.ServiceManifestName);}</span><span class="sxs-lookup"><span data-stu-id="0d439-588">Console.WriteLine("    Deployed applications:"); IList&lt;DeployedServicePackageHealthState&gt; deployedSPHealthStateList = deployedApplicationHealth.DeployedServicePackageHealthStates; foreach (DeployedServicePackageHealthState deployedSPHealthState in deployedSPHealthStateList) { Console.WriteLine("      Application: " + deployedSPHealthState.ApplicationName); Console.WriteLine("        Aggregated Health State: " + deployedSPHealthState.AggregatedHealthState); Console.WriteLine("        Node Name: " + deployedSPHealthState.NodeName); Console.WriteLine("        Service Manifest Name: " + deployedSPHealthState.ServiceManifestName); }</span></span>
                    
            <span data-ttu-id="0d439-589">Überblick über die Integritätsdienst-Ereignisse.</span><span class="sxs-lookup"><span data-stu-id="0d439-589">// List the health events.</span></span>
                <span data-ttu-id="0d439-590">Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = deployedApplicationHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="0d439-590">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = deployedApplicationHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
            <span data-ttu-id="0d439-591">Listen Sie die fehlerhaften auswertungen.</span><span class="sxs-lookup"><span data-stu-id="0d439-591">// List the unhealthy evaluations.</span></span>
            <span data-ttu-id="0d439-592">Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = deployedApplicationHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="0d439-592">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = deployedApplicationHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
            
            <span data-ttu-id="0d439-593">Console.WriteLine(); }} Catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-593">Console.WriteLine(); } } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
            
            <span data-ttu-id="0d439-594">Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-594">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
            
            <span data-ttu-id="0d439-595">"false" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-595">return false; }</span></span>
            
            <span data-ttu-id="0d439-596">"true" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-596">return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-597">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-597">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-598">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-598">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-599">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-599">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-600">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-600">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-601">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-601">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-602">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-602">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-603"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-603"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-604">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-604">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-605"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-605"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-606"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-606"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-607"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-607"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-608"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-608"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-609"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-609"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-610"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-610"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-611"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-611"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-612"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-612"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-613"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-613"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-614"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-614"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-615"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-615"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-616"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-616"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-617">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-617">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-618"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-618"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-619">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-619">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-620">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-620">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-621">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-621">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-622">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-622">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-623">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-623">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-624">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-624">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-625">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-625">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-626">Ruft asynchron ab die Integrität einer bereitgestellten Service Fabric-Anwendung auf dem angegebenen Knoten mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-626">Asynchronously gets the health of a deployed Service Fabric application on the specified node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-627">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-627">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-628">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-628">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-629">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-629">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-630">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-630">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-631">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-631">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-632">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-632">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-633">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-633">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-634"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-634"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-635">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-635">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-636"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-636"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-637"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-637"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-638"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-638"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-639"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-639"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-640"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-640"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-641"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-641"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-642"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-642"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-643"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-643"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-644"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-644"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-645"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-645"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-646"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-646"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-647"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-647"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-648">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-648">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-649"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-649"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-650">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-650">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-651">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-651">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-652">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-652">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="0d439-653">Der Knotenname, in dem die Service Fabric-Anwendung bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-653">The node name where the Service Fabric application is deployed.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-654">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-654">The application health policy used to evaluate entity health.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-655">Ruft asynchron den Zustand einer bereitgestellten Service Fabric-Anwendung, auf dem angegebenen Knoten.</span><span class="sxs-lookup"><span data-stu-id="0d439-655">Asynchronously gets the health of a deployed Service Fabric application on the specified node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-656">Die Integrität einer bereitgestellten Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-656">The health of a deployed Service Fabric application.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-657">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-657">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-658">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-658">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-659">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-659">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-660">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-660">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-661">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-661">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-662">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-662">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-663"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-663"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-664">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-664">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-665"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-665"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-666"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-666"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-667"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-667"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-668"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-668"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-669"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-669"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-670"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-670"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-671"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-671"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-672"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-672"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-673"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-673"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-674"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-674"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-675"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-675"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-676"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-676"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-677">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-677">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-678"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-678"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-679">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-679">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-680">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-680">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-681">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-681">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="0d439-682">Der Knotenname, in dem die Service Fabric-Anwendung bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-682">The node name where the Service Fabric application is deployed.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-683">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-683">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-684">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-684">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-685">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-685">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-686">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-686">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-687">Ruft asynchron ab die Integrität einer bereitgestellten Service Fabric-Anwendung auf dem angegebenen Knoten mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-687">Asynchronously gets the health of a deployed Service Fabric application on the specified node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-688">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-688">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-689">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-689">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-690">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-690">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-691">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-691">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-692">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-692">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-693">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-693">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-694">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-694">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-695"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-695"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-696">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-696">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-697"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-697"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-698"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-698"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-699"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-699"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-700"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-700"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-701"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-701"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-702"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-702"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-703"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-703"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-704"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-704"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-705"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-705"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-706"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-706"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-707"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-707"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-708"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-708"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-709">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-709">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-710"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-710"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-711">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-711">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-712">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-712">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-713">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-713">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="0d439-714">Der Knotenname, in dem die Service Fabric-Anwendung bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-714">The node name where the Service Fabric application is deployed.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-715">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-715">The application health policy used to evaluate the entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-716">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-716">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-717">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-717">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-718">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-718">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-719">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-719">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-720">Ruft asynchron ab die Integrität einer bereitgestellten Service Fabric-Anwendung auf dem angegebenen Knoten mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-720">Asynchronously gets the health of a deployed Service Fabric application on the specified node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-721">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-721">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-722">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-722">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-723">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-723">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-724">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-724">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-725">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-725">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-726">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-726">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-727">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-727">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-728"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-728"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-729">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-729">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-730"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-730"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-731"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-731"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-732"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-732"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-733"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-733"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-734"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-734"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-735"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-735"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-736"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-736"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-737"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-737"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-738"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-738"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-739"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-739"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-740"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-740"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-741"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-741"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-742">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-742">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-743"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-743"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-744">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-744">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-745">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-745">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-746">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-746">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-747">Die Integrität eines Dienstpakets bereitgestellten Service Fabric Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-747">Asynchronously gets the health of a deployed Service Fabric service package by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-748">Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="0d439-748">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-749">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-749">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-750">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-750">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-751">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-751">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-752">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-752">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-753">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-753">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-754">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-754">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-755"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-755"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-756">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-756">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-757"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-757"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-758"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-758"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-759"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-759"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-760"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-760"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-761"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-761"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-762"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-762"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-763"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-763"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-764"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-764"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-765"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-765"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-766"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-766"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-767"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-767"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-768"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-768"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-769">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-769">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-770"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-770"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-771">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-771">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-772">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-772">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-773">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-773">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-774">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-774">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-775">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-775">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-776">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-776">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-777">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-777">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-778">Die Integrität eines Dienstpakets bereitgestellten Service Fabric Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-778">Asynchronously gets the health of a deployed Service Fabric service package by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-779">Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="0d439-779">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="0d439-780">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-780">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="0d439-781">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="0d439-781">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-782">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-782">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-783"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-783"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-784"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-784"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
                <span data-ttu-id="0d439-785">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="0d439-785">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-786">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-786">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-787">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-787">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-788">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-788">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-789">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-789">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-790"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-790"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-791">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-791">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-792">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-792">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-793">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-793">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="0d439-794">Der Name des Diensts Manifestdatei für diesen Service Fabric-Dienst.</span><span class="sxs-lookup"><span data-stu-id="0d439-794">The name of the service manifest file for this Service Fabric service.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="0d439-795">Der Name des Knotens, der für der Service Fabric-Dienst bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0d439-795">The name of the node that the Service Fabric service was deployed to.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-796">Ruft asynchron die Integrität eines Dienstpakets bereitgestellten Service Fabric ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-796">Asynchronously gets the health of a deployed Service Fabric service package.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-797">Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="0d439-797">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="0d439-798">Im folgenden Beispiel wird die Integrität eines Dienstpakets bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="0d439-798">The following example gets the health of a deployed service package.</span></span></para>
          <code language="c#"><span data-ttu-id="0d439-799">Öffentliche statische Bool GetDeployedServicePackageHealth(string clusterConnection) {DeployedApplicationHealth DeployedApplicationHealth; DeployedServicePackageHealth DeployedServicePackageHealth; ApplicationHealth ApplicationHealth; URI-Parameter "ApplicationName" = neue Uri("fabric:/myapp/todo");</span><span class="sxs-lookup"><span data-stu-id="0d439-799">public static bool GetDeployedServicePackageHealth(string clusterConnection) { DeployedApplicationHealth deployedApplicationHealth; DeployedServicePackageHealth deployedServicePackageHealth; ApplicationHealth applicationHealth; Uri applicationName = new Uri("fabric:/myapp/todo");</span></span>
            
                <span data-ttu-id="0d439-800">Mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="0d439-800">// Connect to the cluster.</span></span>
                <span data-ttu-id="0d439-801">FabricClient FabricClient = neue FabricClient(clusterConnection);</span><span class="sxs-lookup"><span data-stu-id="0d439-801">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="0d439-802">Console.WriteLine ("Integrität eines Dienstpakets bereitgestellt:");</span><span class="sxs-lookup"><span data-stu-id="0d439-802">Console.WriteLine("Deployed Service Package Health:");</span></span>
            
                <span data-ttu-id="0d439-803">Wiederholen Sie den {/ / bestimmen Sie die Knoten, in dem die Anwendung bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0d439-803">try { // Determine the nodes where the application has been deployed.</span></span>
                <span data-ttu-id="0d439-804">ApplicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName). Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="0d439-804">applicationHealth = fabricClient.HealthManager.GetApplicationHealthAsync(applicationName).Result;</span></span>
            
                <span data-ttu-id="0d439-805">Abgerufen Sie die bereitgestellte dienstpaketintegrität für jeden Knoten werden.</span><span class="sxs-lookup"><span data-stu-id="0d439-805">// Get the deployed service package health for each node.</span></span>
            <span data-ttu-id="0d439-806">IList&lt;DeployedApplicationHealthState&gt; DeployedApplicationHealthStateList = applicationHealth.DeployedApplicationHealthStates; Foreach (DeployedApplicationHealthState DeployedApplicationHealthState in DeployedApplicationHealthStateList) {/ / Abrufen der Integrität der bereitgestellten Anwendung, die den Namen des Dienst-Manifests enthält und / / die Namen der Knoten, auf dem der Dienst bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0d439-806">IList&lt;DeployedApplicationHealthState&gt; deployedApplicationHealthStateList = applicationHealth.DeployedApplicationHealthStates; foreach (DeployedApplicationHealthState deployedApplicationHealthState in deployedApplicationHealthStateList) { // Get the deployed application health, which contains the service manifest name and // the names of the nodes where the service has been deployed.</span></span>
                <span data-ttu-id="0d439-807">DeployedApplicationHealth = fabricClient.HealthManager.GetDeployedApplicationHealthAsync (Parameter "ApplicationName", deployedApplicationHealthState.NodeName). Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="0d439-807">deployedApplicationHealth = fabricClient.HealthManager.GetDeployedApplicationHealthAsync(applicationName, deployedApplicationHealthState.NodeName).Result;</span></span>
                
                    <span data-ttu-id="0d439-808">Zurück, wenn dieses leer.</span><span class="sxs-lookup"><span data-stu-id="0d439-808">// Return if empty.</span></span>
                    <span data-ttu-id="0d439-809">Wenn (deployedApplicationHealth.DeployedServicePackageHealthStates.Count == 0) "false"; zurückgeben</span><span class="sxs-lookup"><span data-stu-id="0d439-809">if (deployedApplicationHealth.DeployedServicePackageHealthStates.Count == 0) return false;</span></span>
            
                    <span data-ttu-id="0d439-810">Rufen Sie die Integrität der bereitgestellten Dienst-Paket.</span><span class="sxs-lookup"><span data-stu-id="0d439-810">// Get the deployed service package health.</span></span>
                    <span data-ttu-id="0d439-811">DeployedServicePackageHealth = fabricClient.HealthManager.GetDeployedServicePackageHealthAsync (Parameter "ApplicationName", deployedApplicationHealth.DeployedServicePackageHealthStates[0]. ServiceManifestName, deployedApplicationHealthState.NodeName). Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="0d439-811">deployedServicePackageHealth = fabricClient.HealthManager.GetDeployedServicePackageHealthAsync(applicationName, deployedApplicationHealth.DeployedServicePackageHealthStates[0].ServiceManifestName, deployedApplicationHealthState.NodeName).Result;</span></span>
                    
                    <span data-ttu-id="0d439-812">Anzeigen der Integrität bereitgestellter Dienst Paketinformationen.</span><span class="sxs-lookup"><span data-stu-id="0d439-812">// Display the deployed service package health information.</span></span>
            <span data-ttu-id="0d439-813">Console.WriteLine ("Anwendungsname:" + deployedServicePackageHealth.ApplicationName); Console.WriteLine ("Node Name:" + deployedServicePackageHealth.NodeName); Console.WriteLine ("aggregierte Integritätsstatus:" + deployedServicePackageHealth.AggregatedHealthState); Console.WriteLine ("Manifest Dienstname:" + deployedServicePackageHealth.ServiceManifestName);</span><span class="sxs-lookup"><span data-stu-id="0d439-813">Console.WriteLine("  Application Name: " + deployedServicePackageHealth.ApplicationName); Console.WriteLine("    Node Name: " + deployedServicePackageHealth.NodeName); Console.WriteLine("    Aggregated Health State: " + deployedServicePackageHealth.AggregatedHealthState); Console.WriteLine("    Service Manifest Name: " + deployedServicePackageHealth.ServiceManifestName);</span></span>
            
            <span data-ttu-id="0d439-814">Überblick über die Integritätsdienst-Ereignisse.</span><span class="sxs-lookup"><span data-stu-id="0d439-814">// List the health events.</span></span>
                <span data-ttu-id="0d439-815">Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = deployedServicePackageHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="0d439-815">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = deployedServicePackageHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
            <span data-ttu-id="0d439-816">Listen Sie die fehlerhaften auswertungen.</span><span class="sxs-lookup"><span data-stu-id="0d439-816">// List the unhealthy evaluations.</span></span>
            <span data-ttu-id="0d439-817">Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = deployedServicePackageHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="0d439-817">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = deployedServicePackageHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
                
            <span data-ttu-id="0d439-818">Console.WriteLine(); }} Catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-818">Console.WriteLine(); } } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
            
            <span data-ttu-id="0d439-819">Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-819">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                <span data-ttu-id="0d439-820">"false" zurückgeben; } "true"; zurückgeben }</span><span class="sxs-lookup"><span data-stu-id="0d439-820">return false; } return true; }</span></span>
            </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-821">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-821">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-822">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-822">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-823">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-823">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-824">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-824">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-825">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-825">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-826">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-826">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-827"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-827"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-828">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-828">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-829"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-829"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-830"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-830"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-831"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-831"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-832"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-832"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-833"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-833"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-834"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-834"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-835"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-835"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-836"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-836"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-837"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-837"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-838"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-838"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-839"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-839"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-840"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-840"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-841">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-841">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-842"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-842"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-843">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-843">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-844">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-844">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-845">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-845">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="0d439-846">Der Name des Diensts Manifestdatei für diesen Service Fabric-Dienst.</span><span class="sxs-lookup"><span data-stu-id="0d439-846">The name of the service manifest file for this Service Fabric service.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="0d439-847">Der Name des Knotens, der für der Service Fabric-Dienst bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0d439-847">The name of the node that the Service Fabric service was deployed to.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-848">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-848">The application health policy used to evaluate the entity health.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-849">Ruft asynchron die Integrität eines Dienstpakets bereitgestellten Service Fabric ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-849">Asynchronously gets the health of a deployed Service Fabric service package.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-850">Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="0d439-850">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-851">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-851">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-852">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-852">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-853">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-853">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-854">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-854">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-855">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-855">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-856">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-856">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-857"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-857"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-858">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-858">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-859"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-859"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-860"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-860"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-861"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-861"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-862"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-862"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-863"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-863"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-864"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-864"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-865"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-865"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-866"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-866"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-867"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-867"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-868"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-868"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-869"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-869"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-870"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-870"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-871">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-871">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-872"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-872"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-873">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-873">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-874">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-874">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-875">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-875">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="0d439-876">Der Name des Diensts Manifestdatei für diesen Service Fabric-Dienst.</span><span class="sxs-lookup"><span data-stu-id="0d439-876">The name of the service manifest file for this Service Fabric service.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="0d439-877">Der Name des Knotens, der für der Service Fabric-Dienst bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0d439-877">The name of the node that the Service Fabric service was deployed to.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-878">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-878">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-879">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-879">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-880">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-880">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-881">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-881">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-882">Die Integrität eines Dienstpakets bereitgestellten Service Fabric Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-882">Asynchronously gets the health of a deployed Service Fabric service package by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-883">Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="0d439-883">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-884">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-884">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-885">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-885">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-886">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-886">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-887">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-887">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-888">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-888">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-889">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-889">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-890"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-890"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-891">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-891">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-892"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-892"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-893"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-893"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-894"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-894"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-895"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-895"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-896"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-896"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-897"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-897"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-898"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-898"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-899"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-899"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-900"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-900"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-901"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-901"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-902"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-902"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-903"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-903"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-904">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-904">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-905"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-905"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-906">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-906">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-907">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-907">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-908">Der URI der Service Fabric-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="0d439-908">The URI of the Service Fabric application.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="0d439-909">Der Name des Diensts Manifestdatei für diesen Service Fabric-Dienst.</span><span class="sxs-lookup"><span data-stu-id="0d439-909">The name of the service manifest file for this Service Fabric service.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="0d439-910">Der Name des Knotens, der für der Service Fabric-Dienst bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="0d439-910">The name of the node that the Service Fabric service was deployed to.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-911">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-911">The application health policy used to evaluate entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-912">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-912">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-913">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-913">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-914">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-914">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-915">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-915">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-916">Die Integrität eines Dienstpakets bereitgestellten Service Fabric Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-916">Asynchronously gets the health of a deployed Service Fabric service package by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-917">Die Integrität eines Dienstpakets bereitgestellten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="0d439-917">The health of a deployed Service Fabric service package.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-918">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-918">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-919">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-919">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-920">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-920">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-921">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-921">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-922">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-922">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-923">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-923">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-924"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-924"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-925">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-925">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-926"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-926"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-927"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="applicationName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-927"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="applicationName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-928"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-928"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-929"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-929"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-930"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-930"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-931"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-931"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-932"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-932"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-933"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-933"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-934"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-934"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-935"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-935"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-936"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-936"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-937"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-937"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-938">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-938">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-939"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-939"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-940">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-940">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-941">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-941">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-942">Die Beschreibung der Abfrage, die Parameter wie Integritätsrichtlinie definiert filtert usw.</span><span class="sxs-lookup"><span data-stu-id="0d439-942">The query description that defines parameters like health policy, filters etc.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-943">Die Integrität eines Service Fabric-Knotens Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-943">Asynchronously gets the health of a Service Fabric node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-944">Die Integrität eines Service Fabric-Knotens.</span><span class="sxs-lookup"><span data-stu-id="0d439-944">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-945">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-945">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-946">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-946">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-947">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-947">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-948">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-948">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-949">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-949">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-950">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-950">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-951"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-951"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-952">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-952">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-953"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-953"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-954"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-954"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-955"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-955"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-956"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-956"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-957"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-957"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-958"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-958"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-959"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-959"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-960"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-960"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-961"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-961"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-962"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-962"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-963"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-963"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-964">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-964">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-965"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-965"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-966">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-966">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-967">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-967">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-968">Der Name des Service Fabric-Knoten.</span><span class="sxs-lookup"><span data-stu-id="0d439-968">The Service Fabric node name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-969">Ruft asynchron die Integrität eines Service Fabric-Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-969">Asynchronously gets the health of a Service Fabric node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-970">Die Integrität eines Service Fabric-Knotens.</span><span class="sxs-lookup"><span data-stu-id="0d439-970">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="0d439-971">Im folgenden Beispiel wird die Integrität eines Knotens.</span><span class="sxs-lookup"><span data-stu-id="0d439-971">The following example gets the health of a node.</span></span></para>
          <code language="c#"><span data-ttu-id="0d439-972">Öffentliche statische Bool GetNodeHealth(string clusterConnection) {NodeHealth NodeHealth;</span><span class="sxs-lookup"><span data-stu-id="0d439-972">public static bool GetNodeHealth(string clusterConnection) { NodeHealth nodeHealth;</span></span>
            
                <span data-ttu-id="0d439-973">Mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="0d439-973">// Connect to the cluster.</span></span>
            <span data-ttu-id="0d439-974">FabricClient FabricClient = neue FabricClient(clusterConnection);</span><span class="sxs-lookup"><span data-stu-id="0d439-974">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="0d439-975">Abrufen der knotenintegrität an.</span><span class="sxs-lookup"><span data-stu-id="0d439-975">// Get the node health.</span></span>
            <span data-ttu-id="0d439-976">Wiederholen Sie den {NodeHealth = fabricClient.HealthManager.GetNodeHealthAsync("Node1"). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-976">try { nodeHealth = fabricClient.HealthManager.GetNodeHealthAsync("Node1").Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
                
                <span data-ttu-id="0d439-977">Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-977">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                    <span data-ttu-id="0d439-978">"false" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-978">return false; }</span></span>
                
                <span data-ttu-id="0d439-979">Anzeigen der Integritätsinformationen der Knoten an.</span><span class="sxs-lookup"><span data-stu-id="0d439-979">// Display the node health information.</span></span>
                <span data-ttu-id="0d439-980">Console.WriteLine ("Knotenintegrität:"); Console.WriteLine ("Knoten {0}: \ {1\}", nodeHealth.NodeName, nodeHealth.AggregatedHealthState);</span><span class="sxs-lookup"><span data-stu-id="0d439-980">Console.WriteLine("Node Health:"); Console.WriteLine("  Node {0}: {1}", nodeHealth.NodeName, nodeHealth.AggregatedHealthState);</span></span>
                    
            <span data-ttu-id="0d439-981">Überblick über die Integritätsdienst-Ereignisse.</span><span class="sxs-lookup"><span data-stu-id="0d439-981">// List the health events.</span></span>
                    <span data-ttu-id="0d439-982">Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = nodeHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="0d439-982">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = nodeHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
            <span data-ttu-id="0d439-983">Listen Sie die fehlerhaften auswertungen.</span><span class="sxs-lookup"><span data-stu-id="0d439-983">// List the unhealthy evaluations.</span></span>
                    <span data-ttu-id="0d439-984">Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = nodeHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="0d439-984">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = nodeHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
                
            <span data-ttu-id="0d439-985">Console.WriteLine(); "true" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-985">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-986">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-986">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-987">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-987">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-988">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-988">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-989">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-989">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-990">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-990">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-991">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-991">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-992"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-992"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-993">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-993">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-994"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-994"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-995"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-995"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-996"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-996"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-997"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-997"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-998"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-998"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-999"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-999"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1000"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1000"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1001"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1001"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1002"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1002"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1003"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1003"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1004"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1004"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1005">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1005">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1006"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1006"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1007">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1007">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1008">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1008">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1009">Der Name des Service Fabric-Knoten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1009">The Service Fabric node name.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-1010">Die clusterintegritätsrichtlinie verwendet, um den Zustand des Knotens auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1010">The cluster health policy used to evaluate the node health.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-1011">Ruft asynchron die Integrität eines Service Fabric-Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-1011">Asynchronously gets the health of a Service Fabric node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1012">Die Integrität eines Service Fabric-Knotens.</span><span class="sxs-lookup"><span data-stu-id="0d439-1012">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1013">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1013">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1014">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1014">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1015">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1015">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1016">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1016">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1017">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1017">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1018">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1018">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1019"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1019"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1020">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1020">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1021"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1021"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1022"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1022"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1023"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1023"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1024"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1024"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1025"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1025"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1026"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1026"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1027"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1027"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1028"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1028"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1029"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1029"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1030"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1030"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1031"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1031"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1032">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1032">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1033"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1033"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1034">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1034">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1035">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1035">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-1036">Die Beschreibung der Abfrage, die Parameter wie Integritätsrichtlinie definiert filtert usw.</span><span class="sxs-lookup"><span data-stu-id="0d439-1036">The query description that defines parameters like health policy, filters etc.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1037">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1037">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1038">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1038">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1039">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1039">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="0d439-1040">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1040">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1041">Die Integrität eines Service Fabric-Knotens Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1041">Asynchronously gets the health of a Service Fabric node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1042">Die Integrität eines Service Fabric-Knotens.</span><span class="sxs-lookup"><span data-stu-id="0d439-1042">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1043">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1043">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1044">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1044">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1045">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1045">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1046">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1046">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1047">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1047">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1048">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1048">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1049"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1049"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1050">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1050">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1051"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1051"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1052"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1052"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1053"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1053"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1054"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1054"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1055"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1055"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1056"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1056"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1057"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1057"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1058"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1058"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1059"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1059"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1060"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1060"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1061"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1061"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1062">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1062">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1063"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1063"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1064">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1064">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1065">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1065">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1066">Der Service Fabric-Knoten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1066">The Service Fabric node.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1067">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1067">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1068">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1068">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1069">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1069">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="0d439-1070">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1070">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1071">Die Integrität eines Service Fabric-Knotens Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1071">Asynchronously gets the health of a Service Fabric node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1072">Die Integrität eines Service Fabric-Knotens.</span><span class="sxs-lookup"><span data-stu-id="0d439-1072">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1073">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1073">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1074">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1074">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1075">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1075">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1076">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1076">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1077">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1077">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1078">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1078">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1079"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1079"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1080">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1080">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1081"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1081"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1082"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1082"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1083"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1083"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1084"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1084"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1085"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1085"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1086"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1086"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1087"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1087"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1088"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1088"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1089"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1089"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1090"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1090"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1091"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1091"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1092">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1092">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1093"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1093"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1094">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1094">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1095">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1095">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1096">Der Service Fabric-Knoten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1096">The Service Fabric node.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-1097">Die clusterintegritätsrichtlinie verwendet, um den Zustand des Knotens auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1097">The cluster health policy used to evaluate the node health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1098">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1098">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1099">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1099">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1100">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1100">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="0d439-1101">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1101">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1102">Die Integrität eines Service Fabric-Knotens Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1102">Asynchronously gets the health of a Service Fabric node by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1103">Die Integrität eines Service Fabric-Knotens.</span><span class="sxs-lookup"><span data-stu-id="0d439-1103">The health of a Service Fabric node.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1104">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1104">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1105">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1105">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1106">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1106">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1107">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1107">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1108">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1108">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1109">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1109">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1110"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1110"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1111">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1111">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1112"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1112"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1113"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1113"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1114"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1114"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1115"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1115"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1116"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1116"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1117"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1117"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1118"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1118"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1119"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1119"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1120"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1120"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1121"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1121"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1122"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1122"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1123">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1123">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1124"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1124"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1125">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1125">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1126">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1126">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-1127">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-1127">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-1128">Ruft asynchron ab die Integrität einer Service Fabric-Partition mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1128">Asynchronously gets the health of a Service Fabric partition by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1129">Die Integrität einer Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1129">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1130">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1130">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1131">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1131">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1132">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1132">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1133">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1133">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1134">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1134">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1135">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1135">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1136"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1136"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1137">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1137">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1138"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1138"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1139"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1139"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1140"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1140"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1141"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1141"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1142"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1142"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1143"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1143"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1144"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1144"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1145"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1145"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1146"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1146"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1147"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1147"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1148"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1148"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1149">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1149">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1150"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1150"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1151">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1151">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1152">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1152">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1153">Die ID der Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1153">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1154">Ruft asynchron die Integrität einer Service Fabric-Partition ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-1154">Asynchronously gets the health of a Service Fabric partition.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1155">Die Integrität einer Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1155">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="0d439-1156">Im folgenden Beispiel wird die Integrität einer Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1156">The following example gets the health of a partition.</span></span></para>
          <code language="c#"><span data-ttu-id="0d439-1157">Öffentliche statische Bool GetPartitionHealth(string clusterConnection) {PartitionHealth PartitionHealth;</span><span class="sxs-lookup"><span data-stu-id="0d439-1157">public static bool GetPartitionHealth(string clusterConnection) { PartitionHealth partitionHealth;</span></span>
            
                <span data-ttu-id="0d439-1158">Mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="0d439-1158">// Connect to the cluster.</span></span>
            <span data-ttu-id="0d439-1159">FabricClient FabricClient = neue FabricClient(clusterConnection);</span><span class="sxs-lookup"><span data-stu-id="0d439-1159">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="0d439-1160">Abrufen der partitionsintegrität an.</span><span class="sxs-lookup"><span data-stu-id="0d439-1160">// Get the partition health.</span></span>
            <span data-ttu-id="0d439-1161">Wiederholen Sie den {PartitionHealth = fabricClient.HealthManager.GetPartitionHealthAsync (neue Guid("a7206315-e53b-4d05-b59c-e210caa28893")). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-1161">try { partitionHealth = fabricClient.HealthManager.GetPartitionHealthAsync(new Guid("a7206315-e53b-4d05-b59c-e210caa28893")).Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
                
                <span data-ttu-id="0d439-1162">Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-1162">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                    <span data-ttu-id="0d439-1163">"false" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-1163">return false; }</span></span>
                
                <span data-ttu-id="0d439-1164">Anzeigen der Integritätsinformationen der Partition an.</span><span class="sxs-lookup"><span data-stu-id="0d439-1164">// Display the partition health information.</span></span>
                <span data-ttu-id="0d439-1165">Console.WriteLine ("Partitions-Integrität:"); Console.WriteLine ("Partitions-ID:" + partitionHealth.PartitionId); Console.WriteLine ("aggregierte Integritätsstatus:" + partitionHealth.AggregatedHealthState);</span><span class="sxs-lookup"><span data-stu-id="0d439-1165">Console.WriteLine("Partition Health:"); Console.WriteLine("  Partition ID: " + partitionHealth.PartitionId); Console.WriteLine("    Aggregated Health State: " + partitionHealth.AggregatedHealthState);</span></span>
                    
            <span data-ttu-id="0d439-1166">Überblick über die Integritätsdienst-Ereignisse.</span><span class="sxs-lookup"><span data-stu-id="0d439-1166">// List the health events.</span></span>
                    <span data-ttu-id="0d439-1167">Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = partitionHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="0d439-1167">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = partitionHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
                        
            <span data-ttu-id="0d439-1168">Liste der replikatintegritätszustände an.</span><span class="sxs-lookup"><span data-stu-id="0d439-1168">// List the replica health states.</span></span>
                    <span data-ttu-id="0d439-1169">Console.WriteLine ("Replikatintegritätszustände:"); IList&lt;ReplicaHealthState&gt; ReplicaHealthStates = partitionHealth.ReplicaHealthStates; Foreach (ReplicaHealthState ReplicaHealthState in ReplicaHealthStates) {Console.WriteLine ("ID:" + replicaHealthState.Id); Console.WriteLine ("Art:" + replicaHealthState.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + replicaHealthState.AggregatedHealthState); Console.WriteLine ("Partitions-ID:" + replicaHealthState.PartitionId);}</span><span class="sxs-lookup"><span data-stu-id="0d439-1169">Console.WriteLine("    Replica Health States:"); IList&lt;ReplicaHealthState&gt; replicaHealthStates = partitionHealth.ReplicaHealthStates; foreach (ReplicaHealthState replicaHealthState in replicaHealthStates) { Console.WriteLine("      ID: " + replicaHealthState.Id); Console.WriteLine("        Kind: " + replicaHealthState.Kind); Console.WriteLine("        Aggregated Health State: " + replicaHealthState.AggregatedHealthState); Console.WriteLine("        Partition ID: " + replicaHealthState.PartitionId); }</span></span>
                
            <span data-ttu-id="0d439-1170">Listen Sie die fehlerhaften auswertungen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1170">// List the unhealthy evaluations.</span></span>
                <span data-ttu-id="0d439-1171">Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = partitionHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="0d439-1171">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = partitionHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
                
                <span data-ttu-id="0d439-1172">Console.WriteLine(); "true" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-1172">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1173">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1173">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1174">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1174">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1175">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1175">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1176">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1176">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1177">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1177">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1178">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1178">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1179"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1179"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1180">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1180">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1181"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1181"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1182"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1182"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1183"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1183"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1184"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1184"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1185"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1185"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1186"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1186"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1187"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1187"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1188"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1188"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1189"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1189"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1190"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1190"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1191"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1191"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1192">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1192">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1193"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1193"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1194">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1194">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1195">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1195">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1196">Die ID der Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1196">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-1197">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1197">The application health policy used to evaluate the entity health.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-1198">Ruft asynchron die Integrität einer Service Fabric-Partition ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-1198">Asynchronously gets the health of a Service Fabric partition.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1199">Die Integrität einer Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1199">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1200">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1200">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1201">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1201">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1202">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1202">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1203">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1203">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1204">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1204">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1205">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1205">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1206"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1206"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1207">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1207">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1208"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1208"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1209"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1209"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1210"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1210"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1211"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1211"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1212"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1212"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1213"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1213"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1214"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1214"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1215"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1215"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1216"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1216"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1217"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1217"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1218"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1218"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1219">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1219">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1220"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1220"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1221">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1221">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1222">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1222">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-1223">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-1223">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1224">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1224">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1225">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1225">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1226">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1226">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1227">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1227">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1228">Ruft asynchron ab die Integrität einer Service Fabric-Partition mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1228">Asynchronously gets the health of a Service Fabric partition by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1229">Die Integrität einer Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1229">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1230">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1230">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1231">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1231">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1232">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1232">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1233">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1233">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1234">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1234">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1235">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1235">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1236"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1236"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1237">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1237">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1238"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1238"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1239"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1239"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1240"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1240"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1241"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1241"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1242"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1242"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1243"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1243"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1244"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1244"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1245"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1245"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1246"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1246"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1247"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1247"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1248"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1248"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1249">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1249">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1250"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1250"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1251">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1251">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1252">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1252">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1253">Die ID der Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1253">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1254">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1254">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1255">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1255">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1256">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1256">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1257">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1257">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1258">Ruft asynchron ab die Integrität einer Service Fabric-Partition mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1258">Asynchronously gets the health of a Service Fabric partition by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1259">Die Integrität einer Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1259">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1260">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1260">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1261">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1261">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1262">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1262">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1263">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1263">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1264">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1264">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1265">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1265">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1266"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1266"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1267">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1267">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1268"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1268"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1269"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1269"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1270"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1270"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1271"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1271"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1272"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1272"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1273"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1273"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1274"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1274"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1275"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1275"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1276"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1276"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1277"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1277"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1278"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1278"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1279">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1279">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1280"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1280"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1281">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1281">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1282">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1282">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1283">Die ID der Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1283">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-1284">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1284">The application health policy used to evaluate the entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1285">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1285">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1286">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1286">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1287">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1287">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1288">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1288">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1289">Ruft asynchron ab die Integrität einer Service Fabric-Partition mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1289">Asynchronously gets the health of a Service Fabric partition by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1290">Die Integrität einer Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1290">The health of a Service Fabric partition.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1291">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1291">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1292">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1292">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1293">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1293">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1294">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1294">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1295">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1295">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1296">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1296">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1297"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1297"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1298">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1298">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1299"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1299"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1300"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1300"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1301"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1301"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1302"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1302"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1303"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1303"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1304"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1304"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1305"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1305"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1306"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1306"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1307"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1307"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1308"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1308"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1309"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1309"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1310">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1310">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1311"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1311"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1312">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1312">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1313">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1313">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-1314">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-1314">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-1315">Ruft asynchron die Integrität eines Service Fabric-Replikats, die gemäß der Beschreibung der Abfrage ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-1315">Asynchronously gets the health of a Service Fabric replica specified by the query description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1316">Die Integrität eines Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1316">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1317">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1317">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1318">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1318">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1319">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1319">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1320">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1320">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1321">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1321">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1322">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1322">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1323"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1323"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1324">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1324">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1325"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1325"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1326"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1326"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1327"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1327"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1328"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1328"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1329"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1329"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1330"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1330"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1331"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1331"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1332"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1332"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1333"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1333"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1334"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1334"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1335"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1335"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1336">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1336">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1337"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1337"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1338">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1338">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1339">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1339">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1340">Die ID der Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1340">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="0d439-1341">Die ID des Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1341">The ID of the Service Fabric replica.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1342">Ruft asynchron die Integrität eines Service Fabric-Replikats ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-1342">Asynchronously gets the health of a Service Fabric replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1343">Die Integrität eines Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1343">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="0d439-1344">Im folgenden Beispiel wird die Integrität eines Replikats an.</span><span class="sxs-lookup"><span data-stu-id="0d439-1344">The following example gets the health of a replica.</span></span></para>
          <code language="c#"><span data-ttu-id="0d439-1345">Öffentliche statische Bool GetReplicaHealth(string clusterConnection) {ReplicaHealth ReplicaHealth;</span><span class="sxs-lookup"><span data-stu-id="0d439-1345">public static bool GetReplicaHealth(string clusterConnection) { ReplicaHealth replicaHealth;</span></span>
            
                <span data-ttu-id="0d439-1346">Mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="0d439-1346">// Connect to the cluster.</span></span>
            <span data-ttu-id="0d439-1347">FabricClient FabricClient = neue FabricClient(clusterConnection);</span><span class="sxs-lookup"><span data-stu-id="0d439-1347">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
                
                <span data-ttu-id="0d439-1348">Abrufen der replikatintegrität an.</span><span class="sxs-lookup"><span data-stu-id="0d439-1348">// Get the replica health.</span></span>
            <span data-ttu-id="0d439-1349">Wiederholen Sie den {ReplicaHealth = fabricClient.HealthManager.GetReplicaHealthAsync (neue Guid("a7206315-e53b-4d05-b59c-e210caa28893"), 130538257146083818). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-1349">try { replicaHealth = fabricClient.HealthManager.GetReplicaHealthAsync( new Guid("a7206315-e53b-4d05-b59c-e210caa28893"), 130538257146083818).Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
                
                <span data-ttu-id="0d439-1350">Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-1350">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                    <span data-ttu-id="0d439-1351">"false" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-1351">return false; }</span></span>
            
                <span data-ttu-id="0d439-1352">Console.WriteLine ("Replikatintegrität:"); Console.WriteLine ("ID:" + replicaHealth.Id); Console.WriteLine ("aggregierte Integritätsstatus:" + replicaHealth.AggregatedHealthState); Console.WriteLine ("Art:" + replicaHealth.Kind); Console.WriteLine ("Partitions-ID:" + replicaHealth.PartitionId);</span><span class="sxs-lookup"><span data-stu-id="0d439-1352">Console.WriteLine("Replica Health:"); Console.WriteLine("  ID: " + replicaHealth.Id); Console.WriteLine("    Aggregated Health State: " + replicaHealth.AggregatedHealthState); Console.WriteLine("    Kind: " + replicaHealth.Kind); Console.WriteLine("    Partition ID: " + replicaHealth.PartitionId);</span></span>
                
                <span data-ttu-id="0d439-1353">Überblick über die Integritätsdienst-Ereignisse.</span><span class="sxs-lookup"><span data-stu-id="0d439-1353">// List the health events.</span></span>
                    <span data-ttu-id="0d439-1354">Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = replicaHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="0d439-1354">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = replicaHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
                    <span data-ttu-id="0d439-1355">Listen Sie die fehlerhaften auswertungen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1355">// List the unhealthy evaluations.</span></span>
            <span data-ttu-id="0d439-1356">Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = replicaHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="0d439-1356">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = replicaHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
            
                    <span data-ttu-id="0d439-1357">Console.WriteLine(); "true" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-1357">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1358">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1358">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1359">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1359">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1360">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1360">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1361">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1361">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1362">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1362">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1363">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1363">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1364"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1364"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1365">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1365">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1366"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1366"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1367"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1367"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1368"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1368"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1369"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1369"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1370"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1370"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1371"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1371"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1372"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1372"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1373"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1373"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1374"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1374"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1375"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1375"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1376"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1376"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1377">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1377">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1378"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1378"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1379">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1379">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1380">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1380">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-1381">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-1381">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1382">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1382">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1383">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1383">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1384">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1384">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1385">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1385">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1386">Die Integrität eines Service Fabric-Replikats Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1386">Asynchronously gets the health of a Service Fabric replica by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1387">Die Integrität eines Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1387">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1388">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1388">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1389">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1389">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1390">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1390">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1391">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1391">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1392">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1392">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1393">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1393">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1394"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1394"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1395">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1395">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1396"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1396"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1397"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1397"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1398"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1398"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1399"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1399"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1400"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1400"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1401"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1401"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1402"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1402"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1403"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1403"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1404"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1404"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1405"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1405"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1406"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1406"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1407">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1407">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1408"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1408"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1409">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1409">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1410">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1410">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1411">Die ID der Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1411">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="0d439-1412">Die ID des Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1412">The ID of the Service Fabric replica.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-1413">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1413">The application health policy used to evaluate the entity health.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-1414">Ruft asynchron die Integrität eines Service Fabric-Replikats ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-1414">Asynchronously gets the health of a Service Fabric replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1415">Die Integrität eines Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1415">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1416">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1416">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1417">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1417">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1418">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1418">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1419">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1419">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1420">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1420">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1421">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1421">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1422"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1422"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1423">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1423">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1424"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1424"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1425"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1425"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1426"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1426"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1427"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1427"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1428"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1428"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1429"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1429"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1430"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1430"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1431"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1431"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1432"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1432"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1433"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1433"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1434"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1434"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1435">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1435">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1436"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1436"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1437">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1437">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1438">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1438">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1439">Die ID der Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1439">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="0d439-1440">Die ID des Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1440">The ID of the Service Fabric replica.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1441">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1441">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1442">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1442">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1443">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1443">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1444">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1444">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1445">Die Integrität eines Service Fabric-Replikats Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1445">Asynchronously gets the health of a Service Fabric replica by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1446">Die Integrität eines Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1446">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1447">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1447">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1448">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1448">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1449">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1449">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1450">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1450">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1451">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1451">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1452">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1452">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1453"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1453"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1454">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1454">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1455"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1455"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1456"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1456"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1457"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1457"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1458"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1458"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1459"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1459"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1460"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1460"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1461"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1461"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1462"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1462"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1463"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1463"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1464"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1464"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1465"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1465"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1466">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1466">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1467"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1467"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1468">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1468">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1469">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1469">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1470">Die ID der Service Fabric-Partition.</span><span class="sxs-lookup"><span data-stu-id="0d439-1470">The ID of the Service Fabric partition.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="0d439-1471">Die ID des Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1471">The ID of the Service Fabric replica.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-1472">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1472">The application health policy used to evaluate the entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1473">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1473">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1474">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1474">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1475">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1475">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1476">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1476">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1477">Die Integrität eines Service Fabric-Replikats Ruft asynchron mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1477">Asynchronously gets the health of a Service Fabric replica by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1478">Die Integrität eines Service Fabric-Replikats.</span><span class="sxs-lookup"><span data-stu-id="0d439-1478">The health of a Service Fabric replica.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1479">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1479">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1480">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1480">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1481">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1481">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1482">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1482">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1483">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1483">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1484">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1484">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1485"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1485"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1486">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1486">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1487"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1487"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1488"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1488"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1489"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1489"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1490"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1490"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1491"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1491"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1492"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1492"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1493"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1493"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1494"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1494"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1495"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1495"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1496"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1496"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1497"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1497"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1498">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1498">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1499"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1499"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1500">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1500">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1501">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1501">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-1502">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-1502">The query description.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-1503">Ruft asynchron ab der Integrität eines Service Fabric-Dienstes mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1503">Asynchronously gets the health of a Service Fabric service by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1504">Die Integrität eines Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1504">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1505">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1505">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1506">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1506">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1507">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1507">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1508">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1508">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1509">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1509">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1510">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1510">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1511"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1511"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1512">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1512">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1513"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1513"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1514"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-1514"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1515"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1515"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1516"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1516"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1517"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1517"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1518"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1518"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1519"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1519"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1520"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1520"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1521"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1521"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1522"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1522"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1523"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1523"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1524"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1524"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1525">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1525">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1526"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1526"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1527">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1527">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1528">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1528">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1529">Der Name des Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1529">The name of the Service Fabric service.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1530">Ruft asynchron die Integrität eines Service Fabric-Dienstes ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-1530">Asynchronously gets the health of a Service Fabric service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1531">Die Integrität eines Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1531">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="0d439-1532">Im folgenden Beispiel wird die Integrität eines Diensts.</span><span class="sxs-lookup"><span data-stu-id="0d439-1532">The following example gets the health of a service.</span></span></para>
          <code language="c#"><span data-ttu-id="0d439-1533">Öffentliche statische Bool GetServiceHealth(string clusterConnection) {ServiceHealth ServiceHealth; URI-ServiceName = neue Uri("fabric:/myapp/todo/svc1");</span><span class="sxs-lookup"><span data-stu-id="0d439-1533">public static bool GetServiceHealth(string clusterConnection) { ServiceHealth serviceHealth; Uri serviceName = new Uri("fabric:/myapp/todo/svc1");</span></span>
            
                <span data-ttu-id="0d439-1534">Mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="0d439-1534">// Connect to the cluster.</span></span>
                <span data-ttu-id="0d439-1535">FabricClient FabricClient = neue FabricClient(clusterConnection);</span><span class="sxs-lookup"><span data-stu-id="0d439-1535">FabricClient fabricClient = new FabricClient(clusterConnection);</span></span>
            
                <span data-ttu-id="0d439-1536">Rufen Sie die dienstintegrität.</span><span class="sxs-lookup"><span data-stu-id="0d439-1536">// Get the service health.</span></span>
                <span data-ttu-id="0d439-1537">Wiederholen Sie den {ServiceHealth = fabricClient.HealthManager.GetServiceHealthAsync(serviceName). Ergebnis. } catch (Exception e) {Console.WriteLine ("Fehler:" + e.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-1537">try { serviceHealth = fabricClient.HealthManager.GetServiceHealthAsync(serviceName).Result; } catch (Exception e) { Console.WriteLine("Error: " + e.Message);</span></span>
            
                <span data-ttu-id="0d439-1538">Wenn (e.InnerException! = Null) Console.WriteLine ("innere Ausnahme:" + e.InnerException.Message);</span><span class="sxs-lookup"><span data-stu-id="0d439-1538">if (e.InnerException != null) Console.WriteLine("  Inner Exception: " + e.InnerException.Message);</span></span>
                
                <span data-ttu-id="0d439-1539">"false" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-1539">return false; }</span></span>
                    
                <span data-ttu-id="0d439-1540">Console.WriteLine ("Health Service:"); Console.WriteLine ("Service {0}: \ {1\}", serviceHealth.ServiceName, serviceHealth.AggregatedHealthState);</span><span class="sxs-lookup"><span data-stu-id="0d439-1540">Console.WriteLine("Service Health:"); Console.WriteLine("  Service {0}: {1}", serviceHealth.ServiceName, serviceHealth.AggregatedHealthState);</span></span>
                
                <span data-ttu-id="0d439-1541">Liste der Zustände.</span><span class="sxs-lookup"><span data-stu-id="0d439-1541">// List the health states.</span></span>
                    <span data-ttu-id="0d439-1542">Console.WriteLine ("Partition Zustände:"); IList&lt;PartitionHealthState&gt; PartitionHealthStates = serviceHealth.PartitionHealthStates; Foreach (PartitionHealthState PartitionHealthState in PartitionHealthStates) {Console.WriteLine ("aggregierten Integritätsstatus: "+ partitionHealthState.AggregatedHealthState); Console.WriteLine ("Partitions-ID:" + partitionHealthState.PartitionId);}</span><span class="sxs-lookup"><span data-stu-id="0d439-1542">Console.WriteLine("    Partition Health States:"); IList&lt;PartitionHealthState&gt; partitionHealthStates = serviceHealth.PartitionHealthStates; foreach (PartitionHealthState partitionHealthState in partitionHealthStates) { Console.WriteLine("      Aggregated Health State: " + partitionHealthState.AggregatedHealthState); Console.WriteLine("      Partition ID: " + partitionHealthState.PartitionId); }</span></span>
            
                    <span data-ttu-id="0d439-1543">Überblick über die Integritätsdienst-Ereignisse.</span><span class="sxs-lookup"><span data-stu-id="0d439-1543">// List the health events.</span></span>
            <span data-ttu-id="0d439-1544">Console.WriteLine ("Integritätsereignisse:"); IList&lt;HealthEvent&gt; HealthEvents = serviceHealth.HealthEvents; Foreach (HealthEvent-HealthEvent in HealthEvents) {Console.WriteLine ("Integritätsereignis:"); Console.WriteLine ("zuletzt geändert:" + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine ("UTC-Zeitstempel Quelle:" + healthEvent.SourceUtcTimestamp); Console.WriteLine ("ist abgelaufen:" + healthEvent.IsExpired); Console.WriteLine ("Integritätsinformationen:"); Console.WriteLine ("Description:" + healthEvent.HealthInformation.Description); Console.WriteLine ("Quell-ID:" + healthEvent.HealthInformation.SourceId); Console.WriteLine ("Integritätsstatus:" + healthEvent.HealthInformation.HealthState); Console.WriteLine ("-Eigenschaft:" + healthEvent.HealthInformation.Property); Console.WriteLine ("entfernen, wenn abgelaufen:" + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine ("Sequenznummer:" + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine ("Gültigkeitsdauer:" + healthEvent.HealthInformation.TimeToLive);}</span><span class="sxs-lookup"><span data-stu-id="0d439-1544">Console.WriteLine("    Health Events:"); IList&lt;HealthEvent&gt; healthEvents = serviceHealth.HealthEvents; foreach (HealthEvent healthEvent in healthEvents) { Console.WriteLine("      Health Event:"); Console.WriteLine("        Last Modified: " + healthEvent.LastModifiedUtcTimestamp); Console.WriteLine("        Source UTC Timestamp: " + healthEvent.SourceUtcTimestamp); Console.WriteLine("        Is Expired: " + healthEvent.IsExpired); Console.WriteLine("        Health Information:"); Console.WriteLine("          Description: " + healthEvent.HealthInformation.Description); Console.WriteLine("          Source ID: " + healthEvent.HealthInformation.SourceId); Console.WriteLine("          Health State: " + healthEvent.HealthInformation.HealthState); Console.WriteLine("          Property: " + healthEvent.HealthInformation.Property); Console.WriteLine("          Remove When Expired: " + healthEvent.HealthInformation.RemoveWhenExpired); Console.WriteLine("          Sequence Number: " + healthEvent.HealthInformation.SequenceNumber); Console.WriteLine("          Time to Live: " + healthEvent.HealthInformation.TimeToLive); }</span></span>
            
                    <span data-ttu-id="0d439-1545">Listen Sie die fehlerhaften auswertungen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1545">// List the unhealthy evaluations.</span></span>
                <span data-ttu-id="0d439-1546">Console.WriteLine ("fehlerhaften Auswertungen:"); IList&lt;HealthEvaluation&gt; HealthEvaluationList = serviceHealth.UnhealthyEvaluations; Foreach (HealthEvaluation HealthEvaluation in HealthEvaluationList) {Console.WriteLine ("Art:" + healthEvaluation.Kind); Console.WriteLine ("aggregierte Integritätsstatus:" + healthEvaluation.AggregatedHealthState); Console.WriteLine ("Description:" + healthEvaluation.Description);}</span><span class="sxs-lookup"><span data-stu-id="0d439-1546">Console.WriteLine("    Unhealthy Evaluations:"); IList&lt;HealthEvaluation&gt; healthEvaluationList = serviceHealth.UnhealthyEvaluations; foreach (HealthEvaluation healthEvaluation in healthEvaluationList) { Console.WriteLine("      Kind: " + healthEvaluation.Kind); Console.WriteLine("        Aggregated Health State: " + healthEvaluation.AggregatedHealthState); Console.WriteLine("        Description: " + healthEvaluation.Description); }</span></span>
            
                <span data-ttu-id="0d439-1547">Console.WriteLine(); "true" zurückgeben; }</span><span class="sxs-lookup"><span data-stu-id="0d439-1547">Console.WriteLine(); return true; }</span></span>
                </code>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1548">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1548">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1549">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1549">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1550">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1550">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1551">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1551">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1552">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1552">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1553">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1553">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1554"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1554"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1555">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1555">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1556"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1556"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="serviceName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-1557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="serviceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1558"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1558"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1559"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1559"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1560"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1560"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1561"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1561"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1562"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1562"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1563"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1563"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1564"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1564"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1565"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1565"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1566"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1566"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1567"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1567"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1568">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1568">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1569"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1569"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1570">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1570">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1571">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1571">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1572">Der Name des Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1572">The name of the Service Fabric service.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-1573">Die Integritätsrichtlinie für die Anwendung zur Bewertung der Integrität des Diensts.</span><span class="sxs-lookup"><span data-stu-id="0d439-1573">The application health policy used to evaluate service health.</span></span></param>
        <summary>
          <para><span data-ttu-id="0d439-1574">Ruft asynchron die Integrität eines Service Fabric-Dienstes ab.</span><span class="sxs-lookup"><span data-stu-id="0d439-1574">Asynchronously gets the health of a Service Fabric service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1575">Die Integrität eines Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1575">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1576">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1576">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1577">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1577">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1578">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1578">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1579">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1579">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1580">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1580">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1581">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1581">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1582"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang mehr als die angegebene Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1582"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the specified time to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1583">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1583">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1584"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1584"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1585"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="serviceName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-1585"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="serviceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1586"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1586"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1587"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1587"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1588"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1588"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1589"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1589"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1590"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1590"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1591"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1591"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1592"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1592"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1593"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1593"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1594"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1594"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1595"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1595"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1596">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1596">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1597"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1597"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1598">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1598">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1599">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1599">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
        <param name="queryDescription"><span data-ttu-id="0d439-1600">Die Beschreibung der Abfrage.</span><span class="sxs-lookup"><span data-stu-id="0d439-1600">The query description.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1601">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1601">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1602">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1602">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1603">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1603">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1604">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1604">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1605">Ruft asynchron ab der Integrität eines Service Fabric-Dienstes mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1605">Asynchronously gets the health of a Service Fabric service by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1606">Die Integrität eines Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1606">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1607">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1607">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1608">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1608">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1609">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1609">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1610">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1610">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1611">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1611">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1612">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1612">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1613"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1613"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1614">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1614">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1615"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1615"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1616"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-1616"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <see cref="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1617"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1617"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1618"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1618"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1619"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1619"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1620"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1620"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1621"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1621"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1622"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1622"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1623"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1623"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1624"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1624"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1625"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1625"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1626"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1626"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1627">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1627">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1628"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1628"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1629">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1629">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1630">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1630">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1631">Der Name des Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1631">The name of the Service Fabric service.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1632">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1632">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1633">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1633">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1634">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1634">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1635">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1635">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1636">Ruft asynchron ab der Integrität eines Service Fabric-Dienstes mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1636">Asynchronously gets the health of a Service Fabric service by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1637">Die Integrität eines Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1637">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1638">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1638">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1639">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1639">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1640">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1640">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1641">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1641">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1642">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1642">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1643">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1643">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1644"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1644"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1645">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1645">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1646"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1646"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1647"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="serviceName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-1647"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="serviceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1648"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1648"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1649"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1649"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1650"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1650"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1651"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1651"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1652"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1652"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1653"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1653"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1654"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1654"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1655"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1655"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1656"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1656"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1657"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1657"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1658">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1658">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1659"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1659"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1660">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1660">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1661">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1661">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1662">Der Name des Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1662">The name of the Service Fabric service.</span></span></para>
        </param>
        <param name="healthPolicy"><span data-ttu-id="0d439-1663">Die Integritätsrichtlinie für die Anwendung verwendet, um den Entitätszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="0d439-1663">The application health policy used to evaluate the entity health.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="0d439-1664">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="0d439-1664">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="0d439-1665">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="0d439-1665">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="0d439-1666">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1666">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="0d439-1667">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1667">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1668">Ruft asynchron ab der Integrität eines Service Fabric-Dienstes mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="0d439-1668">Asynchronously gets the health of a Service Fabric service by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="0d439-1669">Die Integrität eines Service Fabric-Dienstes.</span><span class="sxs-lookup"><span data-stu-id="0d439-1669">The health of a Service Fabric service.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1670">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1670">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1671">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1671">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1672">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1672">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0d439-1673">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1673">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1674">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="0d439-1674">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="0d439-1675">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1675">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1676"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" />wird zurückgegeben, wenn der Vorgang länger als vom Benutzer angegebenen dauert <paramref name="timeout" /> abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="0d439-1676"><see cref="F:System.Fabric.FabricErrorCode.OperationTimedOut" /> is returned when the operation takes more than the user provided <paramref name="timeout" /> to complete.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1677">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1677">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1678"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1678"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthEntityNotFound" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1679"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="serviceName" /> ist kein gültiger Service Fabric Name.</span><span class="sxs-lookup"><span data-stu-id="0d439-1679"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="serviceName" /> is not a valid Service Fabric Name.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1680"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" />wird zurückgegeben, wenn aufgrund eines Kommunikationsproblems misslingen des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0d439-1680"><see cref="F:System.Fabric.FabricErrorCode.CommunicationError" /> is returned when a communication error caused the operation to fail.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1681"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1681"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1682"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1682"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1683"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1683"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1684"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1684"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1685"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1685"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1686"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1686"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1687"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1687"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1688"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1688"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1689"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1689"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="0d439-1690">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1690">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1691"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" />wird zurückgegeben, wenn der Dienst zum Verarbeiten des Vorgangs zu stark ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1691"><see cref="F:System.Fabric.FabricErrorCode.ServiceTooBusy" /> is returned when the service is too busy to process the operation.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1692">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1692">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1693">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1693">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1694">Das <see cref="T:System.Fabric.Health.HealthReport" />, das gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1694">The <see cref="T:System.Fabric.Health.HealthReport" /> to submit.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1695">Integrität für eine Entität Service Fabric gemeldet.</span><span class="sxs-lookup"><span data-stu-id="0d439-1695">Reports health on a Service Fabric entity.</span></span></para>
        </summary>
        <remarks>
          <para>
             <span data-ttu-id="0d439-1696">Bei ein Cluster geschützt wird, benötigt der Client Integrität Administrator eine Zugriffsberechtigung für die Berichte senden kann.</span><span class="sxs-lookup"><span data-stu-id="0d439-1696">When a cluster is secured, the health client needs administrator permission to be able to send the reports.</span></span>
             <span data-ttu-id="0d439-1697">Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">Herstellen einer Verbindung zu einem Cluster mit den APIs FabricClient</see>.</span><span class="sxs-lookup"><span data-stu-id="0d439-1697">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">connecting to a cluster using the FabricClient APIs</see>.</span></span>
            </para>
          <para>
             <span data-ttu-id="0d439-1698">Weitere Informationen zur Integrität Berichterstattung finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric-Integritätsüberwachung</see>.</span><span class="sxs-lookup"><span data-stu-id="0d439-1698">For more information about health reporting, see <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric health monitoring</see>.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1699">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1699">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1700">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1700">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1701">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1701">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1702">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1702">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1703"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1703"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1704"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1704"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1705"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1705"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1706"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1706"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1707"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1707"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1708"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1708"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1709"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1709"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1710"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1710"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1711"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1711"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1712"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1712"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1713"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1713"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1714">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1714">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1715">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1715">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
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
          <para><span data-ttu-id="0d439-1716">Das <see cref="T:System.Fabric.Health.HealthReport" />, das gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="0d439-1716">The <see cref="T:System.Fabric.Health.HealthReport" /> to submit.</span></span></para>
        </param>
        <param name="sendOptions">
          <para><span data-ttu-id="0d439-1717">Die <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> ab, der steuert, wie der Bericht gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1717">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0d439-1718">Integrität der Berichte auf einem Service Fabric-Entität und übergibt senden Optionen zum Steuern, wie der Bericht gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="0d439-1718">Reports health on a Service Fabric entity and passes send options to control how the report is sent.</span></span></para>
        </summary>
        <remarks>
          <para>
             <span data-ttu-id="0d439-1719">Bei ein Cluster geschützt wird, benötigt der Client Integrität Administrator eine Zugriffsberechtigung für die Berichte senden kann.</span><span class="sxs-lookup"><span data-stu-id="0d439-1719">When a cluster is secured, the health client needs administrator permission to be able to send the reports.</span></span>
             <span data-ttu-id="0d439-1720">Erfahren Sie mehr über <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">Herstellen einer Verbindung mit einem Cluster mithilfe der FabricClient-APIs.</see></span><span class="sxs-lookup"><span data-stu-id="0d439-1720">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster">connecting to a cluster using the FabricClient APIs.</see></span></span></para>
          <para>
             <span data-ttu-id="0d439-1721">Weitere Informationen zur Integrität Berichterstattung finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric-Integritätsüberwachung</see>.</span><span class="sxs-lookup"><span data-stu-id="0d439-1721">For more information about health reporting, see <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-health-introduction">Service Fabric health monitoring</see>.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="0d439-1722">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="0d439-1722">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="0d439-1723">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d439-1723">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="0d439-1724">Wird zurückgegeben, wenn ein null-Verweis an eine Methode übergeben wird akzeptiert, die sie als gültiges Argument keine.</span><span class="sxs-lookup"><span data-stu-id="0d439-1724">Returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="0d439-1725">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1725">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="0d439-1726"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1726"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthStaleReport" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1727"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1727"><see cref="F:System.Fabric.FabricErrorCode.FabricHealthMaxReportsReached" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1728"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1728"><see cref="F:System.Fabric.FabricErrorCode.InvalidCredentialType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1729"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1729"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509FindType" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1730"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1730"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreLocation" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1731"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1731"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509StoreName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1732"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1732"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Thumbprint" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1733"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1733"><see cref="F:System.Fabric.FabricErrorCode.InvalidProtectionLevel" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1734"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1734"><see cref="F:System.Fabric.FabricErrorCode.InvalidX509Store" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1735"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1735"><see cref="F:System.Fabric.FabricErrorCode.InvalidSubjectName" />.</span></span></para>
          <para>
            <span data-ttu-id="0d439-1736"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1736"><see cref="F:System.Fabric.FabricErrorCode.InvalidAllowedCommonNameList" />.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="0d439-1737">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="0d439-1737">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="0d439-1738">E_ACCESSDENIED wird zurückgegeben, wenn die zugriffsprüfung für diesen Vorgang fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="0d439-1738">E_ACCESSDENIED is returned when the access check has failed for this operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>