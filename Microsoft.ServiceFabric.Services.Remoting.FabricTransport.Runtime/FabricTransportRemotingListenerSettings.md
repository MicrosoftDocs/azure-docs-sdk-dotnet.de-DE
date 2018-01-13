<Type Name="FabricTransportRemotingListenerSettings" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings">
  <TypeSignature Language="C#" Value="public class FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportRemotingListenerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportRemotingListenerSettings" />
  <TypeSignature Language="F#" Value="type FabricTransportRemotingListenerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Einstellungen, die den FabricTransport-Listener konfiguriert.
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportRemotingListenerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine neue Instanz der FabricTransportRemotingListenerSettings und Eigenschaften mit den Standardwerten initialisiert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointResourceName">
      <MemberSignature Language="C#" Value="public string EndpointResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.EndpointResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointResourceName As String" />
      <MemberSignature Language="F#" Value="member this.EndpointResourceName : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.EndpointResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            EndpointResourceName handelt es sich um die Namen der endpunktressource in ServiceManifest angegeben. Dient zum Abrufen der Portnummer auf dem Dienst überwacht. 
            </summary>
        <value>
            EndpointResourceName ist der Name der endpunktressource im Dienstmanifest definiert.
            </value>
        <remarks>
            Standardwert EndpointResourceName ist "ServiceEndpoint" </remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderBufferSize">
      <MemberSignature Language="C#" Value="public int HeaderBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderBufferSize : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            HeaderBufferSize stellt die Größe jedes einzelnen Puffers Header in der BufferPool dar.
             </summary>
        <value>To be added.</value>
        <remarks>
                Standard-Wert für die HeaderBufferSize ist 1024 Byte.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderMaxBufferCount">
      <MemberSignature Language="C#" Value="public int HeaderMaxBufferCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderMaxBufferCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderMaxBufferCount" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderMaxBufferCount As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderMaxBufferCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.HeaderMaxBufferCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            HeaderMaxBufferCount stellt die maximale Anzahl der Header-Puffer der BufferPool zugewiesen.
             </summary>
        <value>To be added.</value>
        <remarks>
                Standard-Wert für die HeaderMaxBufferCount ist 1000.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan KeepAliveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KeepAliveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.KeepAliveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.KeepAliveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            KeepAliveTimeout ist, bietet eine Möglichkeit zum Konfigurieren der TCP-Keep-alive-Option.
            </summary>
        <value>KeepAliveTimeout als<see cref="T:System.TimeSpan" /></value>
        <remarks>Standardwert für KeepAliveTimeout Timeout wird als TimeSpan.Zero festgelegt. Gibt an, dass wir die Tcp Keepalive-Option deaktivieren.
            Wenn Sie Loadbalancer verwenden, müssen Sie möglicherweise konfigurieren, um die Loadbalancer zum Schließen der Verbindung einem bestimmten Zeitpunkt zu vermeiden. </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings LoadFrom (string sectionName, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings LoadFrom(string sectionName, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.LoadFrom(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function LoadFrom (sectionName As String, Optional configPackageName As String = null) As FabricTransportRemotingListenerSettings" />
      <MemberSignature Language="F#" Value="static member LoadFrom : string * string -&gt; Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.LoadFrom (sectionName, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName">Der Name des Abschnitts in der Konfigurationsdatei. Wenn es nicht gefunden, löst ArgumentException.</param>
        <param name="configPackageName"> Der Name des Konfigurationspakets. Wenn nicht gefunden "Settings.xml" in der Pfad des Pakets wird ArgumentException ausgelöst. Wenn nicht angegeben ist, lautet der Standardname "Config"</param>
        <summary>
            Lädt die FabricTransport-Einstellungen von einem Abschnitt in der Konfigurationsdatei der Settings - angegeben "Settings.xml" 
            </summary>
        <returns>FabricTransportRemotingListenerSettings</returns>
        <remarks>
            Es folgen die Namen der Parameter, die in der Konfigurationsdatei von Service Fabric Laden Sie die transporteinstellungen erkannt werden bereitgestellt werden soll.
                
                1. MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />in langen Wert.
                2. MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />Wert in Bytes.
                3. Drosselungen für MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />in langen Wert.
                4. SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> Wert.
                5. OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> Wert in Sekunden.
                6. KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> Wert in Sekunden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public long MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxConcurrentCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Drosselungen für MaxConcurrentCalls stellt maximale Anzahl von Nachrichten Dienst aktiv Prozesse gleichzeitig.
             </summary>
        <value>
            Drosselungen für MaxConcurrentCalls ist die Obergrenze aktiver Nachrichten im Dienst.
             </value>
        <remarks>
                Standardwerte-Wert für den Drosselungen für MaxConcurrentCalls liegt und die Anzahl der Prozessoren.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            MaxMessageSize stellt die maximale Größe für eine Nachricht, die in einem mit dieser Einstellung konfigurierten Kanal beim Nachrichtenempfang zulässig.
            </summary>
        <value>Maximale Größe der Nachricht in Bytes.
            </value>
        <remarks>
            Standardwert für MaxMessageSize verwendet beträgt 4.194.304 bytes
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxQueueSize">
      <MemberSignature Language="C#" Value="public long MaxQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxQueueSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxQueueSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.MaxQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die maximale Größe einer Warteschlange, die Nachrichten speichert, während sie für einen mit dieser Einstellung konfigurierten Endpunkt verarbeitet werden. 
            </summary>
        <value> Max Size für eine Warteschlange, die Nachrichten aus dem Kanal empfängt. 
            </value>
        <remarks>
            Standardwert ist 10.000 Nachrichten</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Timeout des Vorgangs zur Regelung den gesamten Prozess des Sendens einer Nachricht, einschließlich, empfängt eine Antwortnachricht für einen Anforderung/Antwort-Dienstvorgang.
             Dieses Timeout gilt auch beim Senden von Antwortnachrichten von einer Rückrufvertragsmethode.
            </summary>
        <value>OperationTimeout als<see cref="T:System.TimeSpan" /></value>
        <remarks>Standardwert für das Timeout des Vorgangs ist als 5 Minuten festgelegt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Anmeldeinformationen für das Sichern der Kommunikation 
             </summary>
        <value>SecurityCredentials als<see cref="T:System.Fabric.SecurityCredentials" /></value>
        <remarks>
             Standardwert für SecurityCredentials ist keine SecurityCredential möglich Typ x509SecurityCredentail <seealso cref="T:System.Fabric.X509Credentials" />oder WindowsCredentials<seealso cref="T:System.Fabric.WindowsCredentials" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="TryLoadFrom">
      <MemberSignature Language="C#" Value="public static bool TryLoadFrom (string sectionName, out Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings remotingListenerSettings, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryLoadFrom(string sectionName, [out] class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings&amp; remotingListenerSettings, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.TryLoadFrom(System.String,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings@,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryLoadFrom (sectionName As String, ByRef remotingListenerSettings As FabricTransportRemotingListenerSettings, Optional configPackageName As String = null) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryLoadFrom : string *  * string -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings.TryLoadFrom (sectionName, remotingListenerSettings, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="remotingListenerSettings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings&amp;" RefType="out" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName">Der Name des Abschnitts in der Konfigurationsdatei. Wenn Sie nicht gefunden, es "false" zurückgibt</param>
        <param name="remotingListenerSettings">Wenn diese Methode zurückgegeben wird das <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> Listenersettings Wenn von der Konfiguration erfolgreich laden. Wenn ein Fehler auftritt, wird seine legt ListenerSettings auf null /&gt; </param>
        <param name="configPackageName"> Der Name des Konfigurationspakets. Wenn nicht gefunden "Settings.xml" in der Pfad des Pakets, es gibt "false". Wenn nicht angegeben ist, lautet der Standardname "Config"</param>
        <summary>
            Die FabricTransport-Einstellungen von einem Abschnitt angegeben, in der Konfigurationsdatei der Settings - laden "Settings.xml" 
            </summary>
        <returns>
          <see cref="T:System.Boolean" />Gibt an, ob die Einstellungen aus der Konfiguration erfolgreich geladen. Gibt true zurück, wenn von der Konfiguration erfolgreich laden, andernfalls "false" zurückgeben.</returns>
        <remarks>
            Es folgen die Namen der Parameter, die in der Konfigurationsdatei von Service Fabric Laden Sie die transporteinstellungen erkannt werden bereitgestellt werden soll.
                
                1. MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />in langen Wert.
                2. MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />Wert in Bytes.
                3. Drosselungen für MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />in langen Wert.
                4. SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> Wert.
                5. OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> Wert in Sekunden.
                6. KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> Wert in Sekunden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>