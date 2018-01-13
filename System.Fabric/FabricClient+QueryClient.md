<Type Name="FabricClient+QueryClient" FullName="System.Fabric.FabricClient+QueryClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.QueryClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/QueryClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.QueryClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.QueryClient" />
  <TypeSignature Language="F#" Value="type FabricClient.QueryClient = class" />
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
      <para>Stellt den Fabric-Client, der zum Ausgeben von Abfragen verwendet werden kann.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync () As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Ruft die Details für alle Anwendungen, die im System erstellten ab. Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync (applicationNameFilter As Uri) As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync applicationNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para>Der Name der Anwendung, die ausführliche Informationen zu erhalten.</para>
        </param>
        <summary>
          <para>
            Ruft die Details an, für alle Anwendungen oder für eine bestimmte Anwendung, die im System erstellt. Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</para>
          <para>Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync (applicationNameFilter As Uri, continuationToken As String) As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para>Der Name der Anwendung, die ausführliche Informationen zu erhalten.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details an, für alle Anwendungen oder für eine bestimmte Anwendung, die im System erstellt. Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</para>
          <para>Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para>Der Name der Anwendung, die ausführliche Informationen zu erhalten.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details an, für alle Anwendungen oder für eine bestimmte Anwendung, die im System erstellt. Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</para>
          <para>Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para>Der Name der Anwendung, die ausführliche Informationen zu erhalten.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>
            Ruft die Details an, für alle Anwendungen oder für eine bestimmte Anwendung, die im System erstellt. Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</para>
          <para>Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync (string applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync(string applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationLoadInformationAsync (applicationName As String) As Task(Of ApplicationLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationLoadInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;" Usage="queryClient.GetApplicationLoadInformationAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI des Instanznamens Anwendung.</para>
        </param>
        <summary>
          <para>Ruft die Last Informationen zur angegebenen Instanz ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen von einer Anwendung als <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync (string applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync(string applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationLoadInformationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;" Usage="queryClient.GetApplicationLoadInformationAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der URI des Instanznamens Anwendung.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die Last Informationen zur angegebenen Instanz ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen von einer Anwendung als <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Das Zeitlimit der Anforderung wurde überschritten.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt; GetApplicationNameAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationNameResult&gt; GetApplicationNameAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt;" Usage="queryClient.GetApplicationNameAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts, der den Anwendungsnamen für abrufen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft den Anwendungsnamen für den angegebenen Dienst ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt. </para>
          <para>Die zurückgegebene Aufgabe enthält den Anwendungsnamen als <see cref="T:System.Fabric.Query.ApplicationNameResult" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync (System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync(class System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationPagedListAsync : System.Fabric.Description.ApplicationQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationPagedListAsync applicationQueryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationQueryDescription" Type="System.Fabric.Description.ApplicationQueryDescription" />
      </Parameters>
      <Docs>
        <param name="applicationQueryDescription">
          <para>Die <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> , der bestimmt, welche Anwendungen abgefragt werden soll.</para>
        </param>
        <summary>
          <para>Ruft die Details der Anwendungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.
            Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.
            Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationList" /> , die die Liste der Anwendungen, die die Filtern in respektieren darstellt der <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> und Anpassung an die Seite.
            Wenn die Beschreibung der bereitgestellten Abfrage keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
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
    <Member MemberName="GetApplicationPagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync (System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync(class System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationPagedListAsync : System.Fabric.Description.ApplicationQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationPagedListAsync (applicationQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationQueryDescription" Type="System.Fabric.Description.ApplicationQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationQueryDescription">
          <para>Die <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> , der bestimmt, welche Anwendungen abgefragt werden soll.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft die Details der Anwendungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.
            Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.
            Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationList" /> , die die Liste der Anwendungen, die die Filtern in respektieren darstellt der <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> und Anpassung an die Seite.
            Wenn die Beschreibung der bereitgestellten Abfrage keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
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
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypeListAsync () As Task(Of ApplicationTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft die Details für alle Anwendungstypen bereitgestellt oder im System bereitgestellt wird.
            Verwenden Sie für weitere Funktionalität <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.
            Diese Methode wird in der Zukunft als veraltet markiert.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Anwendungstypen als <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync (string applicationTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync(string applicationTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypeListAsync (applicationTypeNameFilter As String) As Task(Of ApplicationTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync applicationTypeNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeNameFilter">
          <para>Der Typname der Anwendung zum Abrufen von Diensttypen für.</para>
        </param>
        <summary>
          <para>Ruft die Details für alle Anwendungstypen bereitgestellt oder im System oder für den angegebenen Anwendungstyp bereitgestellt wird.
            Verwenden Sie für weitere Funktionalität <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.
            Diese Methode wird in der Zukunft als veraltet markiert.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Anwendungstypen als <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync (string applicationTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync(string applicationTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync (applicationTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeNameFilter">
          <para>Der Typname der Anwendung zum Abrufen von Diensttypen für.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die Details für alle Anwendungstypen bereitgestellt oder im System oder für den angegebenen Anwendungstyp bereitgestellt wird.
            Verwenden Sie für weitere Funktionalität <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.
            Diese Methode wird in der Zukunft als veraltet markiert.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Anwendungstypen als <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypePagedListAsync () As Task(Of ApplicationTypePagedList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
                    Ruft die Details für alle Anwendungstypen bereitgestellt oder im System bereitgestellt wird. 
                </para>
        </summary>
        <returns>
          <para>
                   Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt. Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.
                   </para>
          <para> 
                   Wenn keine Anwendungstypen die bereitgestellten Filter entsprechen entsprechen, gibt diese Abfrage keine Anwendungstypen statt eines Fehlers an.
                </para>
        </returns>
        <remarks>
          <para>
                    Dies ist eine ausgelagerte Abfrage, d. h., wenn nicht alle Anwendungstypen in eine Seite passen wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken ausgegeben, die zum Abrufen der nächsten Seite verwendet werden kann. Z. B. 10000 Anwendungstypen während eine Seite passt nur die ersten 3000 Anwendungstypen, wird 3000 zurückgegeben.
                    Wenn Sie auf den Rest der Ergebnisse zugreifen möchten, rufen Sie die anschließenden Seiten ab, indem Sie in der nächsten Abfrage das zurückgegebene Fortsetzungstoken verwenden.
                    Ein Fortsetzungstoken null wird zurückgegeben, wenn keine nachfolgenden Seiten vorhanden sind.
                    </para>
          <para>
                    Jede Version einen bestimmten Anwendungstyp ist ein Eintrag in das Ergebnis.
                </para>
        </remarks>
        <remarks>
          <para>
                    Weitere Details zu den hier Anwendungstypen anzuzeigen: <see cref="T:System.Fabric.Query.ApplicationType" />.
                </para>
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
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync (System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync(class System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync(System.Fabric.Description.PagedApplicationTypeQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypePagedListAsync (queryDescription As PagedApplicationTypeQueryDescription) As Task(Of ApplicationTypePagedList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : System.Fabric.Description.PagedApplicationTypeQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PagedApplicationTypeQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>
                    Ein <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> Objekt beschreibt, welche Anwendung Typen zurückgeben.
                    </para>
        </param>
        <summary>
          <para>
                    Ruft die Details für Anwendungstypen bereitgestellt oder QueryDescription Arguments gebotenen bereitgestellt wird, in das System die Filter entsprechen.
                    </para>
        </summary>
        <returns>
          <para>
                   Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt. Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.
                   </para>
          <para> 
                   Wenn keine Anwendungstypen die bereitgestellten Filter entsprechen entsprechen, gibt diese Abfrage keine Anwendungstypen statt eines Fehlers an.
                </para>
        </returns>
        <remarks>
          <para>
                    Dies ist eine ausgelagerte Abfrage, d. h., wenn nicht alle Anwendungstypen in eine Seite passen wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken ausgegeben, die zum Abrufen der nächsten Seite verwendet werden kann. Z. B. 10000 Anwendungstypen während eine Seite passt nur die ersten 3000 Anwendungstypen, wird 3000 zurückgegeben.
                    Wenn Sie auf den Rest der Ergebnisse zugreifen möchten, rufen Sie die anschließenden Seiten ab, indem Sie in der nächsten Abfrage das zurückgegebene Fortsetzungstoken verwenden.
                    Ein Fortsetzungstoken null wird zurückgegeben, wenn keine nachfolgenden Seiten vorhanden sind.
                    </para>
          <para>
                    Jede Version einen bestimmten Anwendungstyp ist ein Eintrag in das Ergebnis.
                </para>
        </remarks>
        <remarks>
          <para>
                    Weitere Details zu den hier Anwendungstypen anzuzeigen: <see cref="T:System.Fabric.Query.ApplicationType" />.
                </para>
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
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync (System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync(class System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync(System.Fabric.Description.PagedApplicationTypeQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : System.Fabric.Description.PagedApplicationTypeQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PagedApplicationTypeQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>
                    Ein <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> Objekt beschreibt, welche Anwendung Typen zurückgeben.
                    </para>
        </param>
        <param name="timeout">
          <para>
                    Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.
                </para>
        </param>
        <param name="cancellationToken">
          <para>
                    Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.
                </para>
        </param>
        <summary>
          <para>
                    Ruft die Details für Anwendungstypen bereitgestellt oder QueryDescription Arguments gebotenen bereitgestellt wird, in das System die Filter entsprechen.
                    </para>
        </summary>
        <returns>
          <para>
                   Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt. Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.
                   </para>
          <para> 
                   Wenn keine Anwendungstypen die bereitgestellten Filter entsprechen entsprechen, gibt diese Abfrage keine Anwendungstypen statt eines Fehlers an.
                </para>
        </returns>
        <remarks>
          <para>
                    Dies ist eine ausgelagerte Abfrage, d. h., wenn nicht alle Anwendungstypen in eine Seite passen wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken ausgegeben, die zum Abrufen der nächsten Seite verwendet werden kann. Z. B. 10000 Anwendungstypen während eine Seite passt nur die ersten 3000 Anwendungstypen, wird 3000 zurückgegeben.
                    Wenn Sie auf den Rest der Ergebnisse zugreifen möchten, rufen Sie die anschließenden Seiten ab, indem Sie in der nächsten Abfrage das zurückgegebene Fortsetzungstoken verwenden.
                    Ein Fortsetzungstoken null wird zurückgegeben, wenn keine nachfolgenden Seiten vorhanden sind.
                    </para>
          <para>
                    Jede Version einen bestimmten Anwendungstyp ist ein Eintrag in das Ergebnis.
                </para>
        </remarks>
        <remarks>
          <para>
                    Weitere Details zu den hier Anwendungstypen anzuzeigen: <see cref="T:System.Fabric.Query.ApplicationType" />.
                </para>
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
    <Member MemberName="GetClusterLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetClusterLoadInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterLoadInformationAsync () As Task(Of ClusterLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetClusterLoadInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;" Usage="queryClient.GetClusterLoadInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft die Clusterinformationen für den Auslastungstest an.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Weitere Informationen finden Sie unter <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen zum Laden der Cluster als <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetClusterLoadInformationAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterLoadInformationAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;" Usage="queryClient.GetClusterLoadInformationAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die Clusterinformationen für den Auslastungstest an.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen zum Laden der Cluster als <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationListAsync (nodeName As String) As Task(Of DeployedApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens für Anwendungen abrufen.</para>
        </param>
        <summary>
          <para>Ruft die Liste der bereitgestellten Anwendung.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Anwendungen als <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName, Uri applicationNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName, class System.Uri applicationNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationListAsync (nodeName As String, applicationNameFilter As Uri) As Task(Of DeployedApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync (nodeName, applicationNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens für Anwendungen abrufen.</para>
        </param>
        <param name="applicationNameFilter">
          <para>Filtern Sie die Ergebnisse, um nur Anwendungen, die entsprechend den Anwendungsnamen gehören.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellte Anwendungen auf einem Knoten mit dem angegebenen Namen ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Anwendungen als <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName, Uri applicationNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName, class System.Uri applicationNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync (nodeName, applicationNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens für Anwendungen abrufen.</para>
        </param>
        <param name="applicationNameFilter">
          <para>Filtern Sie die Ergebnisse, um nur Anwendungen, die entsprechend den Anwendungsnamen gehören.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellte Anwendungen auf einem Knoten mit dem angegebenen Namen ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Anwendungen als <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedCodePackageListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedCodePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <summary>
          <para>Ruft die Liste der bereitgestellten Code-Pakete.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Code-Pakete als <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedCodePackageListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, codePackageNameFilter As String) As Task(Of DeployedCodePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, codePackageNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="codePackageNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</para>
        </param>
        <param name="codePackageNameFilter">
          <para>Filtern Sie die Ergebnisse, um nur die passenden dieser codepaketname enthalten.</para>
        </param>
        <summary>
          <para>Ruft die Liste der bereitgestellten Code-Pakete.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Code-Pakete als <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, codePackageNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="codePackageNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</para>
        </param>
        <param name="codePackageNameFilter">
          <para>Filtern Sie die Ergebnisse, um nur die passenden dieser codepaketname enthalten.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die Liste der bereitgestellten Code-Pakete.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Code-Pakete als <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaDetailAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync (string nodeName, Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaDetailAsync (nodeName As String, partitionId As Guid, replicaId As Long) As Task(Of DeployedServiceReplicaDetail)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaDetailAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;" Usage="queryClient.GetDeployedReplicaDetailAsync (nodeName, partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Knotenname, von dem die Ergebnisse gewünscht sind.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-Id für die die Ergebnisse gewünscht werden.</para>
        </param>
        <param name="replicaId">
          <para>Der Bezeichner für das Replikat oder die Instanz, für die die Ergebnisse gewünscht werden.</para>
        </param>
        <summary>
          <para>Gibt die Details eines Replikats auf dem angegebenen Knoten ausgeführt wird.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen als <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaDetailAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync (string nodeName, Guid partitionId, long replicaId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaDetailAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;" Usage="queryClient.GetDeployedReplicaDetailAsync (nodeName, partitionId, replicaId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Knotenname, von dem die Ergebnisse gewünscht sind.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-Id für die die Ergebnisse gewünscht werden.</para>
        </param>
        <param name="replicaId">
          <para>Der Bezeichner für das Replikat oder die Instanz, für die die Ergebnisse gewünscht werden.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Gibt die Details eines Replikats auf dem angegebenen Knoten ausgeführt wird.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen als <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <summary>
          <para>Ruft die Ansicht der Replikate von einem Knoten ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstreplikate als <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri, partitionIdFilter As Nullable(Of Guid)) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="partitionIdFilter">
          <para>Filtern Sie, sodass Sie Ergebnisse nur Replikate, die mit dieser ID der Partition enthalten</para>
        </param>
        <summary>
          <para>Ruft die Ansicht der Replikate von einem Knoten ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstreplikate als <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, partitionIdFilter As Nullable(Of Guid)) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * string * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, serviceManifestNameFilter, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</para>
        </param>
        <param name="partitionIdFilter">
          <para>Filtern Sie, sodass Sie Ergebnisse nur Replikate, die mit dieser ID der Partition enthalten</para>
        </param>
        <summary>
          <para>Ruft die Ansicht der Replikate von einem Knoten ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstreplikate als <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, Nullable&lt;Guid&gt; partitionIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.String,System.Nullable{System.Guid},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * string * Nullable&lt;Guid&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, serviceManifestNameFilter, partitionIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</para>
        </param>
        <param name="partitionIdFilter">
          <para>Filtern Sie, sodass Sie Ergebnisse nur Replikate, die mit dieser ID der Partition enthalten</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft die Ansicht der Replikate von einem Knoten ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstreplikate als <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServicePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellten dienstpakete für die angegebenen Knoten und die Anwendung ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstpakete als <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String) As Task(Of DeployedServicePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName, serviceManifestNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellten dienstpakete für die angegebenen Knoten und die Anwendung ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstpakete als <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellten dienstpakete für die angegebenen Knoten und die Anwendung ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstpakete als <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServiceTypeListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellte Diensttypen auf die angegebenen Knoten und die Anwendung ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Typen als bereitgestellten Dienste <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServiceTypeListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, serviceTypeNameFilter As String) As Task(Of DeployedServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName, serviceManifestNameFilter, serviceTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>Filtern Sie die Ergebnisse, um nur die übereinstimmenden dieser dienstmanifestname Diensttypen enthalten.</para>
        </param>
        <param name="serviceTypeNameFilter">
          <para>Filtern Sie die Ergebnisse umfassen nur die Diensttypen, die mit diesem Namen übereinstimmen.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellte Diensttypen auf die angegebenen Knoten und die Anwendung ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Typen als bereitgestellten Dienste <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName, serviceManifestNameFilter, serviceTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="applicationName">
          <para>Der Namen der Anwendung.</para>
        </param>
        <param name="serviceManifestNameFilter">
          <para>Filtern Sie die Ergebnisse, um nur die übereinstimmenden dieser dienstmanifestname Diensttypen enthalten.</para>
        </param>
        <param name="serviceTypeNameFilter">
          <para>Filtern Sie die Ergebnisse umfassen nur die Diensttypen, die mit diesem Namen übereinstimmen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellte Diensttypen auf die angegebenen Knoten und die Anwendung ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Typen als bereitgestellten Dienste <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync () As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Ruft die Details für alle Knoten im Cluster ab. Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync (nodeNameFilter As String) As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync nodeNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>Der Name des Knotens für Informationen zu erhalten. Der Name des Knotens wird die Groß-/Kleinschreibung. Ruft alle Knoten im Cluster an, wenn der Name des angegebenen Knotens null ist.</para>
        </param>
        <summary>
          <para>
            Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab. Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync (nodeNameFilter As String, continuationToken As String) As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>Der Name des Knotens für Informationen zu erhalten. Der Name des Knotens wird die Groß-/Kleinschreibung. Ruft alle Knoten ab, wenn der Name des angegebenen Knotens null ist.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
          <returns>
            <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
            <para>Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</para>
          </returns>
        </param>
        <summary>
          <para>
            Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab. Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>Der Name des Knotens für Informationen zu erhalten. Der Name des Knotens wird die Groß-/Kleinschreibung. Ruft alle Knoten ab, wenn der Name des angegebenen Knotens null ist.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>
            Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>Der Name des Knotens für Informationen zu erhalten. Der Name des Knotens wird die Groß-/Kleinschreibung. Ruft alle Knoten ab, wenn der Name des angegebenen Knotens null ist.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>
            Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab. Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, System.Fabric.Query.NodeStatusFilter nodeStatusFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, valuetype System.Fabric.Query.NodeStatusFilter nodeStatusFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.Fabric.Query.NodeStatusFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * System.Fabric.Query.NodeStatusFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, nodeStatusFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="nodeStatusFilter" Type="System.Fabric.Query.NodeStatusFilter" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para>Der Name des Knotens für Informationen zu erhalten. Der Name des Knotens wird die Groß-/Kleinschreibung. Ruft alle Knoten ab, wenn der Name des angegebenen Knotens null ist.</para>
        </param>
        <param name="nodeStatusFilter">
          <para>Der Knoten status(es) der Knoten, um ausführliche Informationen zu erhalten.</para>
        </param>
        <param name="continuationToken">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</param>
        <param name="timeout">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</param>
        <param name="cancellationToken">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</param>
        <summary>
            Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab. Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeLoadInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeLoadInformationAsync (nodeName As String) As Task(Of NodeLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetNodeLoadInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;" Usage="queryClient.GetNodeLoadInformationAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <summary>
          <para>Abrufen von Metriken und Informationen auf dem Knoten geladen werden.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen des Knotens als <see cref="T:System.Fabric.Query.NodeLoadInformation" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeLoadInformationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeLoadInformationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;" Usage="queryClient.GetNodeLoadInformationAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilt die Benachrichtigung, dass Vorgänge abgebrochen werden sollen</para>
        </param>
        <summary>
          <para>Abrufen von Metriken und Informationen auf dem Knoten geladen werden.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen des Knotens als <see cref="T:System.Fabric.Query.NodeLoadInformation" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionAsync (partitionId As Guid) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partitions-ID der Partition zum Abrufen von Details.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für die angegebene Partition ab.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partitions-ID der Partition zum Abrufen von Details.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für die angegebene Partition ab.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts zum Abrufen von Partitionen für.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Partitionen eines Diensts ab. Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri, partitionIdFilter As Nullable(Of Guid)) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts.</para>
        </param>
        <param name="partitionIdFilter">
          <para>Die Partitions-ID der Partition zum Abrufen von Details.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Partitionen eines Diensts oder nur die angegebene Partition ab. Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri, continuationToken As String) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Partitionen eines Diensts ab. Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts.</para>
        </param>
        <param name="partitionIdFilter">
          <para>Die Partitions-ID der Partition zum Abrufen von Details.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Partitionen eines Diensts oder nur die angegebene Partition ab. Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid},System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts.</para>
        </param>
        <param name="partitionIdFilter">
          <para>Die Partitions-ID der Partition zum Abrufen von Details.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Partitionen eines Diensts oder nur die angegebene Partition ab. Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionLoadInformationAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionLoadInformationAsync (partitionId As Guid) As Task(Of PartitionLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionLoadInformationAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;" Usage="queryClient.GetPartitionLoadInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partitions-ID der Partition zum Abrufen von Informationen für geladen.</para>
        </param>
        <summary>
          <para>Ruft die Informationen über die Auslastung der Partition ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen zum Laden einer Partition als <see cref="T:System.Fabric.Query.PartitionLoadInformation" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionLoadInformationAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionLoadInformationAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;" Usage="queryClient.GetPartitionLoadInformationAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partitions-ID der Partition zum Abrufen von Informationen für geladen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die Informationen über die Auslastung der Partition ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen zum Laden einer Partition als <see cref="T:System.Fabric.Query.PartitionLoadInformation" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricCodeVersionListAsync () As Task(Of ProvisionedFabricCodeVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft Details für alle Versionen des Cluster-Code im System bereitgestellt.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Versionen der Service Fabric-Code als <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync (string codeVersionFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync(string codeVersionFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricCodeVersionListAsync (codeVersionFilter As String) As Task(Of ProvisionedFabricCodeVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync codeVersionFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersionFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersionFilter">
          <para>Die Codeversion zum Abrufen der Details für.</para>
        </param>
        <summary>
          <para>Ruft Details für den bestimmten Cluster Codeversion im System bereitgestellt.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Versionen der Service Fabric-Code als <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync (string codeVersionFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync(string codeVersionFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync (codeVersionFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersionFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="codeVersionFilter">
          <para>Codeversion, die ausführliche Informationen zu erhalten.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitspanne für den Vorgang abschließt, bevor TimeoutException ausgelöst wird.</para>
        </param>
        <param name="cancellationToken">
          <para>Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Ruft Details für den bestimmten Cluster Codeversion im System bereitgestellt.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Versionen der Service Fabric-Code als <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricConfigVersionListAsync () As Task(Of ProvisionedFabricConfigVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft Details für alle Cluster-Config-Versionen, die im System bereitgestellt.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Service Fabric Config-Versionen als <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync (string configVersionFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync(string configVersionFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricConfigVersionListAsync (configVersionFilter As String) As Task(Of ProvisionedFabricConfigVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync configVersionFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configVersionFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configVersionFilter">
          <para>Zum Abrufen der Details für die Config-Version.</para>
        </param>
        <summary>
          <para>Ruft Details für einen bestimmten Cluster Config-Version, die im System bereitgestellt.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Service Fabric Config-Versionen als <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync (string configVersionFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync(string configVersionFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync (configVersionFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configVersionFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configVersionFilter">
          <para>Zum Abrufen der Details für die Config-Version.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitspanne für den Vorgang abschließt, bevor TimeoutException ausgelöst wird.</para>
        </param>
        <param name="cancellationToken">
          <para>Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Ruft Details für einen bestimmten Cluster Config-Version, die im System bereitgestellt.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Service Fabric Config-Versionen als <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Replikate einer Partition an. Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid, replicaIdOrInstanceIdFilter As Long) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para>Der Replikat-ID oder Instanzbezeichner Replikate für abgerufen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Replikate einer Partition, die das Replikat oder Instanz Filter und dem Statusfilter übereinstimmen. Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid, continuationToken As String) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Replikate einer Partition an. Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para>Der Replikat-ID oder Instanzbezeichner Replikate für abgerufen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Replikate einer Partition, die mit den Replikaten bzw. Instanzen Filter übereinstimmen. Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Der Partitionsbezeichner der Partition zum Abrufen von Replikaten für.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Replikate einer Partition an. Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.Fabric.Query.ServiceReplicaStatusFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * System.Fabric.Query.ServiceReplicaStatusFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, replicaStatusFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="replicaStatusFilter" Type="System.Fabric.Query.ServiceReplicaStatusFilter" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para>Der Replikat-ID oder Instanzbezeichner Replikate für abgerufen.</para>
        </param>
        <param name="replicaStatusFilter">
          <para>Das Replikat status(es) Replikate für abgerufen.</para>
        </param>
        <param name="timeout">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</param>
        <param name="cancellationToken">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</param>
        <summary>
          <para>
            Ruft die Details für alle Replikate einer Partition, die das Replikat oder Instanz Filter und dem Statusfilter übereinstimmen. Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.Fabric.Query.ServiceReplicaStatusFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * System.Fabric.Query.ServiceReplicaStatusFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, replicaStatusFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="replicaStatusFilter" Type="System.Fabric.Query.ServiceReplicaStatusFilter" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para>Der Replikat-ID oder Instanzbezeichner Replikate für abgerufen.</para>
        </param>
        <param name="replicaStatusFilter">
          <para>Filtern Sie die Ergebnisse, um nur die passenden dieser Status des Replikats einschließen.</para>
        </param>
        <param name="continuationToken">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</param>
        <param name="timeout">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</param>
        <param name="cancellationToken">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</param>
        <summary>
          <para>
            Ruft die Details für alle Replikate einer Partition, die das Replikat oder Instanz Filter und dem Statusfilter übereinstimmen. Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</para>
        </returns>
        <remarks>
          <para>
                Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität. </para>
          <para>
                Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync (Guid partitionId, long replicaIdOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaLoadInformationAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaLoadInformationAsync (partitionId As Guid, replicaIdOrInstanceId As Long) As Task(Of ReplicaLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaLoadInformationAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;" Usage="queryClient.GetReplicaLoadInformationAsync (partitionId, replicaIdOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaIdOrInstanceId">
          <para>Der Replikat-ID (stateful Service) oder die Instanz-ID (statusfreien Dienst).</para>
        </param>
        <summary>
          <para>Erhalten Sie eine Liste der Metrik und ihre Arbeitslast auf einem Replikat aus.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen Laden des Replikats <see cref="T:System.Fabric.Query.ReplicaLoadInformation" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync (Guid partitionId, long replicaIdOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaLoadInformationAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaLoadInformationAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;" Usage="queryClient.GetReplicaLoadInformationAsync (partitionId, replicaIdOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaIdOrInstanceId">
          <para>Der Replikat-ID (stateful Service) oder die Instanz-ID (statusfreien Dienst).</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Erhalten Sie eine Liste der Metrik und ihre Arbeitslast auf einem Replikat aus.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen Laden des Replikats <see cref="T:System.Fabric.Query.ReplicaLoadInformation" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberListAsync (applicationName As Uri) As Task(Of ServiceGroupMemberList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Anwendungsname der Gruppe "Dienst".</para>
        </param>
        <summary>
          <para>Abrufen von Dienst Gruppenmitgliedern einer Anwendung.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Gruppenmitglieder als Dienst <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName, Uri serviceNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberListAsync (applicationName As Uri, serviceNameFilter As Uri) As Task(Of ServiceGroupMemberList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync (applicationName, serviceNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Anwendungsname der Gruppe "Dienst".</para>
        </param>
        <param name="serviceNameFilter">
          <para>Der Dienstname der Dienstgruppe.</para>
        </param>
        <summary>
          <para>Abrufen von Dienst Gruppenmitgliedern einer Anwendung.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Gruppenmitglieder als Dienst <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName, Uri serviceNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync (applicationName, serviceNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Anwendungsname der Gruppe "Dienst".</para>
        </param>
        <param name="serviceNameFilter">
          <para>Der Dienstname der Dienstgruppe.</para>
        </param>
        <param name="timeout">
          <para>Das Timeout des Vorgangs.</para>
        </param>
        <param name="cancellationToken">
          <para>Benachrichtigt, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Partitionen eines Diensts ab. Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Gruppenmitglieder als Dienst <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberTypeListAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of ServiceGroupMemberTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Anwendungsname des Typs der Dienstgruppe.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die anwendungstypversion der Dienstgruppe.</para>
        </param>
        <summary>
          <para>Rufen Sie Service Gruppenmitglieder Fehlertypen Dienstgruppen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Dienst Gruppe Elementtypen als <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberTypeListAsync (applicationTypeName As String, applicationTypeVersion As String, serviceGroupTypeNameFilter As String) As Task(Of ServiceGroupMemberTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion, serviceGroupTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceGroupTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Anwendungsname des Typs der Dienstgruppe.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die anwendungstypversion der Dienstgruppe.</para>
        </param>
        <param name="serviceGroupTypeNameFilter">
          <para>Der Name des Diensttyps Gruppe abgerufen werden soll.</para>
        </param>
        <summary>
          <para>Rufen Sie Service Gruppenmitglieder Fehlertypen Dienstgruppen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Dienst Gruppe Elementtypen als <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion, serviceGroupTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceGroupTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Anwendungsname des Typs der Dienstgruppe.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die anwendungstypversion der Dienstgruppe.</para>
        </param>
        <param name="serviceGroupTypeNameFilter">
          <para>Der Name des Diensttyps Gruppe abgerufen werden soll.</para>
        </param>
        <param name="timeout">
          <para>Das Timeout des Vorgangs.</para>
        </param>
        <param name="cancellationToken">
          <para>Benachrichtigt, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Rufen Sie Service Gruppenmitglieder Fehlertypen Dienstgruppen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Dienst Gruppe Elementtypen als <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Name der abzurufenden Dienste für die Anwendung.</para>
        </param>
        <summary>
          <para>
            Ruft die Informationen zu allen Diensten, die an die Anwendung, die durch den Namen der Anwendung URI angegebenen gehören. Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri, serviceNameFilter As Uri) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Name der abzurufenden Dienste für die Anwendung.</para>
        </param>
        <param name="serviceNameFilter">
          <para>Der Name der Dienste für ausführliche Informationen zu erhalten.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Dienste einer Anwendung oder nur den angegebenen Dienst ab. Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri, serviceNameFilter As Uri, continuationToken As String) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Name der abzurufenden Dienste für die Anwendung.</para>
        </param>
        <param name="serviceNameFilter">
          <para>Der Name der Dienste für ausführliche Informationen zu erhalten.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Dienste einer Anwendung oder nur den angegebenen Dienst ab. Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Name der abzurufenden Dienste für die Anwendung.</para>
        </param>
        <param name="serviceNameFilter">
          <para>Der Name der Dienste für ausführliche Informationen zu erhalten.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Dienste einer Anwendung oder nur den angegebenen Dienst ab. Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Der Name der abzurufenden Dienste für die Anwendung.</para>
        </param>
        <param name="serviceNameFilter">
          <para>Der Name der Dienste für ausführliche Informationen zu erhalten.</para>
        </param>
        <param name="continuationToken">
          <para>Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>
            Ruft die Details für alle Dienste einer Anwendung oder nur den angegebenen Dienst ab. Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt; GetServiceNameAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceNameResult&gt; GetServiceNameAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceNameAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceNameAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt;" Usage="queryClient.GetServiceNameAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para>Die Id der Partition, die den Dienstnamen für abrufen.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft den Dienstnamen für die angegebene Partition ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält, der Dienstname als <see cref="T:System.Fabric.Query.ServiceNameResult" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServicePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync (System.Fabric.Description.ServiceQueryDescription serviceQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync(class System.Fabric.Description.ServiceQueryDescription serviceQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServicePagedListAsync : System.Fabric.Description.ServiceQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServicePagedListAsync serviceQueryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceQueryDescription" Type="System.Fabric.Description.ServiceQueryDescription" />
      </Parameters>
      <Docs>
        <param name="serviceQueryDescription">
          <para>Die <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> , der bestimmt, welche Dienste abgefragt werden soll.</para>
        </param>
        <summary>
          <para>Ruft die Details für alle Dienste einer Anwendung oder die angegebenen Dienste, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen. Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt. Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ServiceList" /> , die die Liste der Dienste, die die Filtern in respektieren darstellt der <see cref="T:System.Fabric.Query.ServiceList" /> und Anpassung an die Seite.
            Wenn der bereitgestellte abfragebeschreibung keine passende Dienste verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
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
    <Member MemberName="GetServicePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync (System.Fabric.Description.ServiceQueryDescription serviceQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync(class System.Fabric.Description.ServiceQueryDescription serviceQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServicePagedListAsync : System.Fabric.Description.ServiceQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServicePagedListAsync (serviceQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceQueryDescription" Type="System.Fabric.Description.ServiceQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceQueryDescription">
          <para>Die <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> , der bestimmt, welche Dienste abgefragt werden soll.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft die Details für alle Dienste einer Anwendung oder die angegebenen Dienste, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen. Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt. Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ServiceList" /> , die die Liste der Dienste, die die Filtern in respektieren darstellt der <see cref="T:System.Fabric.Query.ServiceList" /> und Anpassung an die Seite.
            Wenn der bereitgestellte abfragebeschreibung keine passende Dienste verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
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
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypeListAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of ServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Typname der Anwendung zum Abrufen von Diensttypen für.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die anwendungstypversion Diensttypen für abgerufen.</para>
        </param>
        <summary>
          <para>Ruft die Liste der Typen ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste von Diensttypen als <see cref="T:System.Fabric.Query.ServiceTypeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypeListAsync (applicationTypeName As String, applicationTypeVersion As String, serviceTypeNameFilter As String) As Task(Of ServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion, serviceTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Typname der Anwendung zum Abrufen von Diensttypen für.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die anwendungstypversion Diensttypen für abgerufen.</para>
        </param>
        <param name="serviceTypeNameFilter">
          <para>Der Name des abzurufenden Details für den Diensttyp.</para>
        </param>
        <summary>
          <para>Ruft die Liste der Typen ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste von Diensttypen als <see cref="T:System.Fabric.Query.ServiceTypeList" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion, serviceTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Typname der Anwendung zum Abrufen von Diensttypen für.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die anwendungstypversion Diensttypen für abgerufen.</para>
        </param>
        <param name="serviceTypeNameFilter">
          <para>Der Name des abzurufenden Details für den Diensttyp.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft die Liste der Typen ab.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Liste von Diensttypen als <see cref="T:System.Fabric.Query.ServiceTypeList" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUnplacedReplicaInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync (string serviceName, Guid partitionId, bool onlyQueryPrimaries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync(string serviceName, valuetype System.Guid partitionId, bool onlyQueryPrimaries) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetUnplacedReplicaInformationAsync(System.String,System.Guid,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUnplacedReplicaInformationAsync (serviceName As String, partitionId As Guid, onlyQueryPrimaries As Boolean) As Task(Of UnplacedReplicaInformation)" />
      <MemberSignature Language="F#" Value="member this.GetUnplacedReplicaInformationAsync : string * Guid * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;" Usage="queryClient.GetUnplacedReplicaInformationAsync (serviceName, partitionId, onlyQueryPrimaries)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="onlyQueryPrimaries" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="onlyQueryPrimaries">
          <para>Zurückkehren Sie nur die nicht positionierte Replikat Diagnose nur die versuchte primären replikatplatzierungen, um die Ausgabe zu beschränken.</para>
        </param>
        <summary>
          <para>Diagnoseinformationen über Dienste mit nicht positionierte Replikate abrufen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen eines nicht positionierte Replikats als <see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Dieser Vorgang ist ein Timeout von 60 Sekunden.</para>
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUnplacedReplicaInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync (string serviceName, Guid partitionId, bool onlyQueryPrimaries, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync(string serviceName, valuetype System.Guid partitionId, bool onlyQueryPrimaries, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetUnplacedReplicaInformationAsync(System.String,System.Guid,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetUnplacedReplicaInformationAsync : string * Guid * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;" Usage="queryClient.GetUnplacedReplicaInformationAsync (serviceName, partitionId, onlyQueryPrimaries, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="onlyQueryPrimaries" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name des Diensts.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="onlyQueryPrimaries">
          <para>Zurückkehren Sie nur die nicht positionierte Replikat Diagnose nur die versuchte primären replikatplatzierungen, um die Ausgabe zu beschränken.</para>
        </param>
        <param name="timeout">
          <para>Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</para>
        </param>
        <param name="cancellationToken">
          <para>Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</para>
        </param>
        <summary>
          <para>Diagnoseinformationen über Dienste mit nicht positionierte Replikate abrufen.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</para>
          <para>Die zurückgegebene Aufgabe enthält die Informationen eines nicht positionierte Replikats als <see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />.</para>
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
          <para>
                Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>