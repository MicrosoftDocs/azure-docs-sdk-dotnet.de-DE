<Type Name="FabricClient+InfrastructureServiceClient" FullName="System.Fabric.FabricClient+InfrastructureServiceClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/InfrastructureServiceClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.InfrastructureServiceClient" />
  <TypeSignature Language="F#" Value="type FabricClient.InfrastructureServiceClient = class" />
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
      <para>Stellt Methoden zum Ausführen von Vorgängen Infrastruktur bereit.</para>
      <para>Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</para>
    </summary>
    <remarks>
      <para>Die InfrastructureService muss aktiviert sein, bevor dieser Client verwendet werden kann. Die InfrastructureService wird nur auf einige Infrastrukturen unterstützt.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="InvokeInfrastructureCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureCommandAsync (Uri serviceName, string command);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureCommandAsync(class System.Uri serviceName, string command) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureCommandAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeInfrastructureCommandAsync (serviceName As Uri, command As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureCommandAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureCommandAsync (serviceName, command)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name der Ziel-Infrastruktur-Dienstinstanz.</para>
        </param>
        <param name="command">
          <para>Der Text des Befehls, der aufgerufen werden soll.  Der Inhalt des Befehls ist Infrastruktur spezifisch.</para>
        </param>
        <summary>
          <para>Ruft asynchron einen administrativen-Befehl auf der Dienstinstanz des angegebenen Infrastruktur auf.</para>
        </summary>
        <returns>
          <para>Die Antwort vom Dienst Infrastruktur. Das Format der Antwort ist eine JSON-Zeichenfolge. Der Inhalt der Antwort wird, hängt davon ab, welcher Befehl ausgegeben wurde.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureCommandAsync (Uri serviceName, string command, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureCommandAsync(class System.Uri serviceName, string command, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureCommandAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureCommandAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureCommandAsync (serviceName, command, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name der Ziel-Infrastruktur-Dienstinstanz.</para>
        </param>
        <param name="command">
          <para>Der Text des Befehls, der aufgerufen werden soll.  Der Inhalt des Befehls ist Infrastruktur spezifisch.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron einen administrativen-Befehl für einen Dienst Infrastruktur auf.</para>
        </summary>
        <returns>
          <para>Die Antwort vom Dienst Infrastruktur. Das Format der Antwort ist eine JSON-Zeichenfolge. Der Inhalt der Antwort wird, hängt davon ab, welcher Befehl ausgegeben wurde.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureQueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureQueryAsync (Uri serviceName, string command);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureQueryAsync(class System.Uri serviceName, string command) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureQueryAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeInfrastructureQueryAsync (serviceName As Uri, command As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureQueryAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureQueryAsync (serviceName, command)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name der Ziel-Infrastruktur-Dienstinstanz.</para>
        </param>
        <param name="command">
          <para>Der Text des Befehls, der aufgerufen werden soll.  Der Inhalt des Befehls ist Infrastruktur spezifisch.</para>
        </param>
        <summary>
          <para>Ruft asynchron eine nur-Lese Abfrage auf der Dienstinstanz des angegebenen Infrastruktur auf.</para>
        </summary>
        <returns>
          <para>Die Antwort vom Dienst Infrastruktur. Das Format der Antwort ist eine JSON-Zeichenfolge. Der Inhalt der Antwort wird, hängt davon ab, welcher Befehl ausgegeben wurde.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeInfrastructureQueryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; InvokeInfrastructureQueryAsync (Uri serviceName, string command, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; InvokeInfrastructureQueryAsync(class System.Uri serviceName, string command, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.InfrastructureServiceClient.InvokeInfrastructureQueryAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeInfrastructureQueryAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="infrastructureServiceClient.InvokeInfrastructureQueryAsync (serviceName, command, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="command" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Name der Ziel-Infrastruktur-Dienstinstanz.</para>
        </param>
        <param name="command">
          <para>Der Text des Befehls, der aufgerufen werden soll.  Der Inhalt des Befehls ist Infrastruktur spezifisch.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron eine nur-Lese Abfrage auf der Dienstinstanz des angegebenen Infrastruktur auf.</para>
        </summary>
        <returns>
          <para>Die Antwort vom Dienst Infrastruktur. Das Format der Antwort ist eine JSON-Zeichenfolge. Der Inhalt der Antwort wird, hängt davon ab, welcher Befehl ausgegeben wurde.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>