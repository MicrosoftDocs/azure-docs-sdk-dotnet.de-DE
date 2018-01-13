<Type Name="ServicePartitionResolver" FullName="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver">
  <TypeSignature Language="C#" Value="public class ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServicePartitionResolver extends System.Object implements class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class ServicePartitionResolver&#xA;Implements IServicePartitionResolver" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolver = class&#xA;    interface IServicePartitionResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            Implementiert die Partition Konfliktlöser Dienstklasse, die verwendet die <see cref="T:System.Fabric.FabricClient">FabricClients </see> <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> Methode für die Dienst-Auflösung und einen Back-off/Wiederholungsmechanismus bei Fehlern von dieser Methode implementiert.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createFabricClient As CreateFabricClientDelegate)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver createFabricClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
      </Parameters>
      <Docs>
        <param name="createFabricClient">Delegat, der Fabric-Client zu erstellen.</param>
        <summary>
            Instanziiert eine ServicePartitionResolver, die den angegebenen Delegaten instanziieren FabricClient aufrufen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver connectionEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="connectionEndpoints">Array von-Endpunkte des Clusters.</param>
        <summary>
            Instanziiert eine ServicePartitionResolver, der angegebenen ConnectionEndpoints verwendet, um eine neue Instanz der dem FabricClient zu erstellen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient, Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate recreateFabricClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient, class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate recreateFabricClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate,Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createFabricClient As CreateFabricClientDelegate, recreateFabricClient As CreateFabricClientDelegate)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate * Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (createFabricClient, recreateFabricClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
        <Parameter Name="recreateFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
      </Parameters>
      <Docs>
        <param name="createFabricClient">Delegieren Sie zum Erstellen des Fabric-Clients.</param>
        <param name="recreateFabricClient">Zu den Fabric-Client erneut zu erstellenden Delegaten.</param>
        <summary>
          <para>
            Instanziiert eine ServicePartionResolver, das Aufrufen der erste Delegat zum Abrufen der <see cref="T:System.Fabric.FabricClient">FabricClient.</see>.
            Während der Auflösung von Partition wird Wenn FabricClient Objekt verworfen ruft und der zweite Delegat bereitgestellt wird, sie den zweiten Delegaten der FabricClient erneut abgerufen. Der zweite Delegat bietet eine Möglichkeit, geben Sie eine alternative Möglichkeit zum Abrufen oder FabricClient erstellen, wenn mit dem ersten Delegaten FabricClient erstellt werden freigegeben.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.FabricClientSettings settings, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.FabricClientSettings * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (settings, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="settings">Fabric-Client-Einstellungen.</param>
        <param name="connectionEndpoints">Array von-Endpunkte des Clusters.</param>
        <summary>
            Instanziiert eine ServicePartitionResolver, verwendet den angegebenen FabricClient-Einstellungen und die ConnectionEndpoints um eine neue Instanz der FabricClient zu erstellen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.SecurityCredentials credential, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.SecurityCredentials,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.SecurityCredentials * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (credential, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">Die Sicherheitsanmeldeinformationen für die Fabric-Client.</param>
        <param name="connectionEndpoints">Array von-Endpunkte des Clusters.</param>
        <summary>
            Instanziiert eine ServicePartitionResolver, verwendet die angegebenen Anmeldeinformationen und die ConnectionEndpoints, um eine neue Instanz der FabricClient zu erstellen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.SecurityCredentials credential, System.Fabric.FabricClientSettings settings, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, class System.Fabric.FabricClientSettings settings, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.SecurityCredentials,System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, settings As FabricClientSettings, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.SecurityCredentials * System.Fabric.FabricClientSettings * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (credential, settings, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">Die Sicherheitsanmeldeinformationen für die Fabric-Client.</param>
        <param name="settings">Fabric-Client-Einstellungen.</param>
        <param name="connectionEndpoints">Array von-Endpunkte des Clusters.</param>
        <summary>
            Instanziiert eine ServicePartitionResolver, verwendet die angegebenen Anmeldeinformationen, FabricClient Einstellungen und die ConnectionEndpoints um eine neue Instanz der FabricClient zu erstellen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMaxRetryBackoffInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultMaxRetryBackoffInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultMaxRetryBackoffInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultMaxRetryBackoffInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultMaxRetryBackoffInterval : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die maximale Backoff-Standardzeit von ServicePartitionResolvers ResolveAsync-Methode verwendet wird, und wiederholen Sie dann, wenn er aufgerufen wird, ohne explizite Angabe der MaxRetryBackoffInterval-Argument. Der Standardwert ist 5 Sekunden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultResolveTimeout">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultResolveTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultResolveTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultResolveTimeout As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultResolveTimeout : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Standardeinstellung zu beheben, Timeouts pro versuchen Sie es von der ResolveAsync-Methode des verwendeten <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /> beim ohne explizite Angabe der ResolveTimeoutPerTry Argument aufrufen. Der Standardwert ist 30 Sekunden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDefault">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver GetDefault ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver GetDefault() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetDefault () As ServicePartitionResolver" />
      <MemberSignature Language="F#" Value="static member GetDefault : unit -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die standardmäßigen ServicePartitionResolver ab.
            <remarks><para>Die Standard-Partition Konfliktlöser Dienstinstanz verwendet die lokale <see href="https://docs.microsoft.com/en-us/dotnet/api/system.fabric.fabricclient#System_Fabric_FabricClient__ctor">Fabric-Client</see>. Wenn Sie die ServicePartitionResolver verwenden, zum Auflösen der Dienste, die auf einem remote-Cluster ausgeführt werden, ist die empfohlene Vorgehensweise erstellen eine ServicePartitionResolver über die entsprechenden Endpunkte oder FabricClient und aktualisieren Sie die Standardeinstellung ServicePartitionResolver.</para></remarks></summary>
        <returns>Standardwert<see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveAsync : System.Fabric.ResolvedServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (previousRsp, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">Die aufgelösten Dienstpartition, die der Client über den früheren Aufruf der Methode ResolveAsync() erhalten haben.</param>
        <param name="cancellationToken">
          <para>
            Das CancellationToken, das diesen Vorgang beobachtet wird. Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.
            </para>
        </param>
        <summary>
            Löst eine Partition des angegebenen Diensts durch den Aufruf des FabricClient <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode mit Back-off/Wiederholen auf Fehler mit möglichem Wiederholungsversuch. Dies geschieht in der aufgelösten Dienstpartition, die über einen früheren Aufruf der Methode ResolveAsync() erhalten haben, wurde. Diese methodenüberladung ist in Fällen verwendet, in dem der Client weiß, dass die aufgelösten Dienstpartition, die nicht mehr gültig ist.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.
            </returns>
        <remarks>
          <para>
            Diese Methode, die bei allen vorübergehende Ausnahmen, die wiederholt werden. Für Fälle, in denen Sie die maximale Ausführungszeit auf einen dieser Methode beschränken möchten, erstellen Sie eine <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">, maximale Ausführungszeit zugeordnete Abbruchtoken</see> und dieses Abbruchtoken an diese Methode übergeben.
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            Diese Methode kann eine FabricServiceNotFoundExcepion auslösen, wenn der Dienst, zuvor gelöst wurde, nicht mehr im Cluster vorhanden ist.
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (serviceUri, partitionKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri">Der Name der Dienstinstanz zu beheben.</param>
        <param name="partitionKey">
          <para>
            <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Schlüssel</see> , bestimmt die Zielpartition der Dienstinstanz. Die <see cref="T:System.Fabric.ServicePartitionKind">Partitionsschema</see> angegeben im Schlüssel sollten Übereinstimmung das Partitionierungsschema verwendet, um die Instanz zu erstellen.
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            Das CancellationToken, das diesen Vorgang beobachtet wird. Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.
            </para>
        </param>
        <summary>
          <para>
            Löst eine Partition des angegebenen Diensts durch den Aufruf des FabricClient <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode. Dies wird verwendet, die Standardeinstellungen für <see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout">Timeout</see> und <see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval">Backoff-Wiederholung</see> Intervallen.
            </para>
        </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.
            </returns>
        <remarks>
          <para>
            Diese Methode, die bei allen vorübergehende Ausnahmen, die wiederholt werden. Für Fälle, in denen Sie die maximale Ausführungszeit auf einen dieser Methode beschränken möchten, erstellen Sie eine <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">, maximale Ausführungszeit zugeordnete Abbruchtoken</see> und dieses Abbruchtoken an diese Methode übergeben.
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            Diese Methode kann eine FabricServiceNotFoundExcepion auslösen, wenn keine Service-Instanz im angegebenen ServiceUri übereinstimmende Cluster vorhanden ist.
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            Diese Methode kann eine FabricException auslösen, wenn in der ServicePartitionKey angegebene Schema nicht mit das Schema verwendet, um die Dienstinstanz erstellen übereinstimmt.
            Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">Fehlern und Ausnahmen</see> für allgemeine FabricClient Fehlerbehandlung.
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;&#xA;override this.ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (previousRsp, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">Die aufgelösten Dienstpartition, die der Client über den früheren Aufruf der Methode ResolveAsync() erhalten haben.</param>
        <param name="resolveTimeoutPerTry">Das Timeout überschritten wird, um FabricClient des <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode </param>
        <param name="maxRetryBackoffInterval">
          <para>
            Das maximale Intervall, und wiederholen Sie dann beim Backoff FabricClients <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode, die durch eine Ausnahme mit möglichem Wiederholungsversuch fehlschlägt. Die tatsächlichen Backoff-Intervall ist einem zufälligen Zeitintervall kleiner oder gleich der angegebenen MaxRetryBackoffInterval also.
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            Das CancellationToken, das diesen Vorgang beobachtet wird. Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.
            </para>
        </param>
        <summary>
            Löst eine Partition des angegebenen Diensts durch den Aufruf des FabricClient <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode mit Back-off/Wiederholen auf Fehler mit möglichem Wiederholungsversuch. Dies geschieht in der aufgelösten Dienstpartition, die über einen früheren Aufruf der Methode ResolveAsync() erhalten haben, wurde. Diese methodenüberladung ist in Fällen verwendet, in dem der Client weiß, dass die aufgelösten Dienstpartition, die nicht mehr gültig ist.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.
            </returns>
        <remarks>
          <para>
            Diese Methode, die bei allen vorübergehende Ausnahmen, die wiederholt werden. Für Fälle, in denen Sie die maximale Ausführungszeit auf einen dieser Methode beschränken möchten, erstellen Sie eine <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">, maximale Ausführungszeit zugeordnete Abbruchtoken</see> und dieses Abbruchtoken an diese Methode übergeben.
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            Diese Methode kann eine FabricServiceNotFoundExcepion auslösen, wenn der Dienst, zuvor gelöst wurde, nicht mehr im Cluster vorhanden ist.
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;&#xA;override this.ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (serviceUri, partitionKey, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri">Der Name der Dienstinstanz zu beheben.</param>
        <param name="partitionKey">
          <para>
            <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Schlüssel</see> , bestimmt die Zielpartition der Dienstinstanz. Die <see cref="T:System.Fabric.ServicePartitionKind">Partitionsschema</see> angegeben im Schlüssel sollten Übereinstimmung das Partitionierungsschema verwendet, um die Instanz zu erstellen.
            </para>
        </param>
        <param name="resolveTimeoutPerTry">Das Timeout überschritten wird, um FabricClient des <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode.</param>
        <param name="maxRetryBackoffInterval">
          <para>
            Das maximale Intervall, und wiederholen Sie dann beim Backoff FabricClients <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />Methode, die durch eine Ausnahme mit möglichem Wiederholungsversuch fehlschlägt. Die tatsächlichen Backoff-Intervall ist einem zufälligen Zeitintervall kleiner oder gleich der angegebenen MaxRetryBackoffInterval also.
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            Das CancellationToken, das diesen Vorgang beobachtet wird. Es wird verwendet, um dem Vorgang zu benachrichtigen, dass es abgebrochen werden soll.
            </para>
        </param>
        <summary>
            Löst eine Partition des angegebenen Diensts durch den Aufruf des FabricClient <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> Methode mit dem angegebenen Timeout und den Back-off/Wiederholen auf Fehler mit möglichem Wiederholungsversuch.
            </summary>
        <returns>
            Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt. Das Ergebnis von der Aufgabe ist die <see cref="T:System.Fabric.ResolvedServicePartition" /> -Objekt, das die Informationen über die aufgelösten Dienstpartition einschließlich Dienstendpunkte enthält.
            </returns>
        <remarks>
          <para>
            Diese Methode, die bei allen vorübergehende Ausnahmen, die wiederholt werden. Für Fälle, in denen Sie die maximale Ausführungszeit auf einen dieser Methode beschränken möchten, erstellen Sie eine <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">, maximale Ausführungszeit zugeordnete Abbruchtoken</see> und dieses Abbruchtoken an diese Methode übergeben.
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            Diese Methode kann eine FabricServiceNotFoundExcepion auslösen, wenn keine Service-Instanz im angegebenen ServiceUri übereinstimmende Cluster vorhanden ist.
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            Dies kann eine FabricException auslösen, wenn es sich bei in der ServicePartitionKey angegebene Schema nicht mit das Schema verwendet, um die Dienstinstanz erstellen übereinstimmt.
            Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">Fehlern und Ausnahmen</see> für Weitere Informationen.
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SetDefault">
      <MemberSignature Language="C#" Value="public static void SetDefault (Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver defaultServiceResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetDefault(class Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver defaultServiceResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.SetDefault(Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub SetDefault (defaultServiceResolver As ServicePartitionResolver)" />
      <MemberSignature Language="F#" Value="static member SetDefault : Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver -&gt; unit" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.SetDefault defaultServiceResolver" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="defaultServiceResolver" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />
      </Parameters>
      <Docs>
        <param name="defaultServiceResolver">Der neue Standardwert</param>
        <summary>
            Die Standardeinstellung ServicePartitionResolver wird aktualisiert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>