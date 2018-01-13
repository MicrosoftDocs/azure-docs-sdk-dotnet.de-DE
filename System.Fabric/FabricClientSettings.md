<Type Name="FabricClientSettings" FullName="System.Fabric.FabricClientSettings">
  <TypeSignature Language="C#" Value="public sealed class FabricClientSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricClientSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClientSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClientSettings" />
  <TypeSignature Language="F#" Value="type FabricClientSettings = class" />
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
      <para>Stellt die Konfigurationseinstellungen für die <see cref="T:System.Fabric.FabricClient" /> Klasse.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClientSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClientSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricClientSettings" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthTokenBufferSize">
      <MemberSignature Language="C#" Value="public long AuthTokenBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AuthTokenBufferSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthTokenBufferSize As Long" />
      <MemberSignature Language="F#" Value="member this.AuthTokenBufferSize : int64 with get, set" Usage="System.Fabric.FabricClientSettings.AuthTokenBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, der Puffergröße verwendet, wenn ein Authentifizierungstoken von Azure Active Directory abgerufen.
            </summary>
        <value>
            Gibt die Größe des Puffers in Bytes zurück.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientFriendlyName">
      <MemberSignature Language="C#" Value="public string ClientFriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientFriendlyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ClientFriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientFriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.ClientFriendlyName : string with get, set" Usage="System.Fabric.FabricClientSettings.ClientFriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab, oder legt Sie den Anzeigenamen der Client, der angezeigt wird in Service Fabric-ablaufverfolgungen für das Debuggen fest.</para>
        </summary>
        <value>
          <para>Der angezeigte Name der Client, der in Service Fabric-ablaufverfolgungen zum Debuggen angezeigt wird.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist null, und der Anzeigename der Client automatisch intern als GUID generiert wird.</para>
          <para>Wenn mehrere Clients vom gleichen Prozess oder auf demselben Knoten erstellt werden können, wird empfohlen, einen eindeutigen Bezeichner an den Namen angefügt werden soll.
            Beispiel: MyProcessIdentifier-{Guid}.
            Dadurch wird sichergestellt, dass ablaufverfolgungen für die Clients unterschiedliche Aktionen nachverfolgen, die sie generiert.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ConnectionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectionIdleTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ConnectionIdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dieser Parameter wurde als veraltet markiert. Dies wird in der nächsten Version entfernt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectionInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectionInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectionInitializationTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Timeout nach dem die aktuelle Gatewayadresse reagiert nicht mit einer gültigen Verbindung einen anderen andere Adresse wird zufällig ausgewählt aus das Gateway Adressen Auflistung.</para>
        </summary>
        <value>
          <para>Das Timeout, nachdem die aktuelle Gatewayadresse mit einer gültigen Verbindung keine Antwort empfangen wird.</para>
        </value>
        <remarks>
          <para>Der Standardwert der <see cref="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" /> Eigenschaft beträgt 2 Sekunden.</para>
          <para>Die <see cref="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" /> Eigenschaft muss kleiner als der Wert, der die <see cref="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" /> Eigenschaft.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthOperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthOperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthOperationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthOperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthOperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthOperationTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthOperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt das Timeout auf Integrität vorgangsanforderungen vom Client zum Gateway.</para>
        </summary>
        <value>
          <para>Das Timeout auf Integrität vorgangsanforderungen vom Client zum Gateway.</para>
        </value>
        <remarks>
          <para>Der Standardwert der <see cref="P:System.Fabric.FabricClientSettings.HealthOperationTimeout" /> Eigenschaft ist 120 Sekunden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthReportRetrySendInterval">
      <MemberSignature Language="C#" Value="public TimeSpan HealthReportRetrySendInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthReportRetrySendInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthReportRetrySendInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthReportRetrySendInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt das Wiederholungsintervall an, welche cloudintegrität Berichte, die nicht noch vom Health Manager bestätigt wurde erneut gesendet werden.</para>
        </summary>
        <value>
          <para>Das Wiederholungsintervall, welche cloudintegrität Berichte, die nicht noch vom Health Manager bestätigt wurde erneut gesendet werden.</para>
        </value>
        <remarks>
          <para>Der Standardwert der <see cref="P:System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" /> Eigenschaft beträgt 30 Sekunden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthReportSendInterval">
      <MemberSignature Language="C#" Value="public TimeSpan HealthReportSendInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthReportSendInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthReportSendInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthReportSendInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthReportSendInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt das Intervall an, an dem Integritätsberichte zum Health Manager gesendet wurden.</para>
        </summary>
        <value>
          <para>Das Intervall an, welche, das Integrität Berichte auf den Integritätsdienst gesendet werden.</para>
        </value>
        <remarks>
          <para>Der Standardwert der <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> Eigenschaft beträgt 30 Sekunden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveInterval">
      <MemberSignature Language="C#" Value="public TimeSpan KeepAliveInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KeepAliveInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.KeepAliveInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.KeepAliveInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft das Intervall, in dem die <see cref="T:System.Fabric.FabricClient" /> führt ping für den Endpunkt verbunden.</para>
        </summary>
        <value>
          <para>Das Intervall, in dem die <see cref="T:System.Fabric.FabricClient" /> führt ping für den Endpunkt verbunden.</para>
        </value>
        <remarks>
          <para>Der Standardwert der <see cref="P:System.Fabric.FabricClientSettings.KeepAliveInterval" /> Eigenschaft beträgt 0 Sekunden.</para>
          <para>Diese Eigenschaft kann nicht aktualisiert werden, nachdem die <see cref="T:System.Fabric.FabricClient" /> wird geöffnet.
            Einstellung diese Eigenschaft löst eine <see cref="T:System.ArgumentException" /> Ausnahme.</para>
          <para>
            <see cref="T:System.Fabric.FabricClient" />weiterhin pingen, solange es ausstehende Vorgänge verfügt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationCacheUpdateTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan NotificationCacheUpdateTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NotificationCacheUpdateTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.NotificationCacheUpdateTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property NotificationCacheUpdateTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NotificationCacheUpdateTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.NotificationCacheUpdateTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt das Timeout für das Aktualisieren des lokalen Caches als Antwort auf dienstbenachrichtigungen. Der Standardwert ist 30 Sekunden.</para>
        </summary>
        <value>
          <para>Das Timeout für die Reaktion auf Benachrichtigungen Service den lokalen Cache aktualisieren.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationGatewayConnectionTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan NotificationGatewayConnectionTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NotificationGatewayConnectionTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.NotificationGatewayConnectionTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property NotificationGatewayConnectionTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NotificationGatewayConnectionTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.NotificationGatewayConnectionTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt das Timeout für eine erneute Verbindungsprotokolls ausgeführt, wenn der Client für den dienstbenachrichtigungen registriert hat. Der Standardwert ist 30 Sekunden. </para>
        </summary>
        <value>
          <para>Das Timeout für eine erneute Verbindungsprotokolls ausgeführt, wenn der Client für den dienstbenachrichtigungen registriert hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionLocationCacheBucketCount">
      <MemberSignature Language="C#" Value="public long PartitionLocationCacheBucketCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PartitionLocationCacheBucketCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.PartitionLocationCacheBucketCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionLocationCacheBucketCount As Long" />
      <MemberSignature Language="F#" Value="member this.PartitionLocationCacheBucketCount : int64 with get, set" Usage="System.Fabric.FabricClientSettings.PartitionLocationCacheBucketCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ermittelt oder definiert die Bucketanzahl, die von der Client-Dienst Auflösung Cache verwendet.</para>
        </summary>
        <value>
          <para>Die Bucketanzahl, die durch den der Client-Dienst Auflösung Cache verwendet wird.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist 1024.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionLocationCacheLimit">
      <MemberSignature Language="C#" Value="public long PartitionLocationCacheLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PartitionLocationCacheLimit" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionLocationCacheLimit As Long" />
      <MemberSignature Language="F#" Value="member this.PartitionLocationCacheLimit : int64 with get, set" Usage="System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die maximale Anzahl von zwischengespeicherten Speicherort Einträge auf dem Client.</para>
        </summary>
        <value>
          <para>Die maximale Anzahl der zwischengespeicherten Speicherort Einträge auf dem Client.</para>
        </value>
        <remarks>
          <para>Der Standardwert der <see cref="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" /> Eigenschaft ist 1000.</para>
          <para>Die <see cref="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" /> Eigenschaft kann nicht aktualisiert werden. Einstellung diese Eigenschaft löst eine <see cref="T:System.ArgumentException" /> Ausnahme.</para>
          <para>Die ältesten Einträge werden zuerst verworfen, wenn das CacheLimit erreicht ist. Der Standardwert ist 100.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceChangePollInterval">
      <MemberSignature Language="C#" Value="public TimeSpan ServiceChangePollInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ServiceChangePollInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceChangePollInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ServiceChangePollInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ServiceChangePollInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt ihn fest das Timeout für Änderung des benachrichtigungsanforderungen vom Client an das Gateway für alle registrierten Rückrufe.</para>
        </summary>
        <value>
          <para>Das Timeout für Service Change Notification Anforderungen vom Client an das Gateway für alle registrierten Rückrufe.</para>
        </value>
        <remarks>
          <para>Der Standardwert der <see cref="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" /> Eigenschaft ist 120 Sekunden.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>