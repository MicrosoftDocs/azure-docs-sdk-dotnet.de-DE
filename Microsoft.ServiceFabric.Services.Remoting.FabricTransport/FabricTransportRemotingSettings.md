<Type Name="FabricTransportRemotingSettings" FullName="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings">
  <TypeSignature Language="C#" Value="public class FabricTransportRemotingSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FabricTransportRemotingSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricTransportRemotingSettings" />
  <TypeSignature Language="F#" Value="type FabricTransportRemotingSettings = class" />
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
            Stellt eine Einstellungen, die die FabricTransport-Kommunikation konfiguriert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricTransportRemotingSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine neue FabricTransportRemotingSettings mit Standardwerten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" />
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
            Ruft ab oder legt die maximale Zeitspanne für die Verbindung erfolgreich hergestellt werden.
            </summary>
        <value>Die ConnectTimeout als <see cref="T:System.TimeSpan" />.</value>
        <remarks>Standardwert für ConnectTimeout Timeout wird als 5 Sekunden festgelegt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HeaderBufferSize">
      <MemberSignature Language="C#" Value="public int HeaderBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HeaderBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderBufferSize : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderBufferSize" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderMaxBufferCount" />
      <MemberSignature Language="VB.NET" Value="Public Property HeaderMaxBufferCount As Integer" />
      <MemberSignature Language="F#" Value="member this.HeaderMaxBufferCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.HeaderMaxBufferCount" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" />
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
            Abrufen oder Festlegen der KeepAliveTimeout, die eine Möglichkeit zum Konfigurieren der TCP-Keep-alive-Option bereitstellt.
            </summary>
        <value>Die KeepAliveTimeout als <see cref="T:System.TimeSpan" />.</value>
        <remarks>Standardwert für KeepAliveTimeout Timeout wird als TimeSpan.Zero festgelegt. Gibt an, dass wir die Tcp Keepalive-Option deaktivieren.
            Wenn Sie Loadbalancer verwenden, müssen Sie diese konfigurieren, um die Loadbalancer zum Schließen der Verbindung einem bestimmten Zeitpunkt zu vermeiden. </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings LoadFrom (string sectionName, string filepath = null, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings LoadFrom(string sectionName, string filepath, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.LoadFrom(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function LoadFrom (sectionName As String, Optional filepath As String = null, Optional configPackageName As String = null) As FabricTransportRemotingSettings" />
      <MemberSignature Language="F#" Value="static member LoadFrom : string * string * string -&gt; Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.LoadFrom (sectionName, filepath, configPackageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sectionName" Type="System.String" />
        <Parameter Name="filepath" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName">Der Name des Abschnitts in der Konfigurationsdatei. Wenn keine gefunden Abschnitt in der Konfigurationsdatei wird ArgumentException ausgelöst.</param>
        <param name="filepath">Der vollständige Pfad der Datei, in dem die Einstellungen aus geladen werden. Wenn nicht angegeben, wird zuerst versucht, Standardwert Konfigurationspaket "Config" laden, wenn es gefunden anschließend Laden von Einstellungen für "ClientExeName.Settings.xml", die im Client Ausführungsverzeichnis vorhanden. </param>
        <param name="configPackageName"> Der Name des Konfigurationspakets. Wenn die Null oder leer, es für die Datei in den FilePath überprüft.</param>
        <summary>
            Lädt die FabricTransport-Einstellungen aus einem SectionName in der Konfigurationsdatei angegeben. Konfigurationsdatei kann angegeben werden, mithilfe den Dateipfad oder den Namen des Konfigurationspakets in das Manifest angegeben.
            Zunächst wird versucht, mit ConfigPackageName Config zu laden. Wenn ConfigPackageName nicht angegeben ist wiederholen Sie dann aus dem Dateipfad geladen.
            </summary>
        <returns>Die FabricTransportRemotingSettings</returns>
        <remarks>
            Es folgen die Namen der Parameter, die in der Konfigurationsdatei von Service Fabric Laden Sie die transporteinstellungen erkannt werden bereitgestellt werden soll.
                
                1. MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />in langen Wert.
                2. MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />Wert in Bytes.
                3. Drosselungen für MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />in langen Wert.
                4. SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> Wert.
                5. OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> Wert in Sekunden.
                6. KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> Wert in Sekunden.
                7. ConnectTimeoutInMilliseconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" /> Wert in Millisekunden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public long MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />
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
            Ruft ab oder legt die maximale Anzahl von Nachrichten aktiv Dienstprozesse auf einmal.
             </summary>
        <value>
            Der Drosselungen für MaxConcurrentCalls ist die Obergrenze aktiver Nachrichten im Dienst.
             </value>
        <remarks>
                Standardwert für den Drosselungen für MaxConcurrentCalls ist 16 * Anzahl der Prozessoren.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMessageSize">
      <MemberSignature Language="C#" Value="public long MaxMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMessageSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />
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
            Ruft ab oder legt die maximale Größe für eine Nachricht, die empfangen werden kann, in einem Kanal, der mit dieser Einstellung konfiguriert.
            </summary>
        <value>Die maximale Größe der Nachricht in Bytes.
            </value>
        <remarks>
            Standardwert für MaxMessageSize verwendet beträgt 4.194.304 bytes
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxQueueSize">
      <MemberSignature Language="C#" Value="public long MaxQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxQueueSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxQueueSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxQueueSize : int64 with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />
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
            Ruft ab oder legt die maximale Größe einer Warteschlange, die Nachrichten speichert, während sie für einen mit dieser Einstellung konfigurierten Endpunkt verarbeitet werden. 
            </summary>
        <value>Die maximale Größe für eine Warteschlange, die Nachrichten aus dem Kanal empfängt. 
            </value>
        <remarks>
            Standardwert ist 10.000 Nachrichten</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" />
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
            Abrufen oder Festlegen des Vorgangs Timeout zur Regelung den gesamten Prozess des Sendens einer Nachricht, einschließlich, empfängt eine Antwortnachricht für einen Anforderung/Antwort-Dienstvorgang.
             Dieses Timeout gilt auch beim Senden von Antwortnachrichten von einer Rückrufvertragsmethode.
            </summary>
        <value>Der OperationTimeout als <see cref="T:System.TimeSpan" />.</value>
        <remarks>Standardwert für das Timeout des Vorgangs wird als 5 Minuten festgelegt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" />
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
             Ruft ab oder legt die Anmeldeinformationen für das Sichern der Kommunikation. 
             </summary>
        <value>Die Anmeldeinformationen sollten als <see cref="T:System.Fabric.SecurityCredentials" />.
             </value>
        <remarks>
             Standardwert für SecurityCredentials ist None.
             SecurityCredential kann der Typ x509SecurityCredentail <seealso cref="T:System.Fabric.X509Credentials" />oder WindowsCredentials <seealso cref="T:System.Fabric.WindowsCredentials" />.
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryLoadFrom">
      <MemberSignature Language="C#" Value="public static bool TryLoadFrom (string sectionName, out Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings settings, string filepath = null, string configPackageName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryLoadFrom(string sectionName, [out] class Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings&amp; settings, string filepath, string configPackageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.TryLoadFrom(System.String,Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings@,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryLoadFrom (sectionName As String, ByRef settings As FabricTransportRemotingSettings, Optional filepath As String = null, Optional configPackageName As String = null) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryLoadFrom : string *  * string * string -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.TryLoadFrom (sectionName, settings, filepath, configPackageName)" />
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
        <Parameter Name="settings" Type="Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings&amp;" RefType="out" />
        <Parameter Name="filepath" Type="System.String" />
        <Parameter Name="configPackageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sectionName">Der Name des Abschnitts in der Konfigurationsdatei. Wenn keine gefunden Abschnitt in der Konfigurationsdatei es "false" zurückgeben.</param>
        <param name="settings">Wenn diese Methode zurückgegeben wird das <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings" /> Einstellungen Wenn von der Konfiguration erfolgreich laden. Wenn ein Fehler auftritt, legt Einstellungen auf null. </param>
        <param name="filepath">Der vollständige Pfad der Datei, in dem die Einstellungen aus geladen werden. Wenn nicht angegeben, wird zuerst versucht, Standardwert Konfigurationspaket "Config" laden, wenn es gefunden anschließend Laden von Einstellungen für "ClientExeName.Settings.xml", die im Client Ausführungsverzeichnis vorhanden. </param>
        <param name="configPackageName">Der Name des Konfigurationspakets. Wenn die Null oder leer, es für die Datei in den FilePath überprüft.</param>
        <summary>
            Versuchen Sie, die FabricTransport-Einstellungen aus einer in der Konfigurationsdatei angegebenen SectionName zu laden.
            Konfigurationsdatei kann angegeben werden, mithilfe den Dateipfad oder den Namen des Konfigurationspakets in das Manifest angegeben.
            Zunächst wird versucht, mit ConfigPackageName Config zu laden. Wenn ConfigPackageName nicht angegeben ist wiederholen Sie dann aus dem Dateipfad geladen.
            </summary>
        <returns>
          <see cref="T:System.Boolean" />Gibt an, ob die Einstellungen aus der Konfiguration erfolgreich geladen. Gibt true zurück, wenn von der Konfiguration erfolgreich laden, andernfalls "false" zurückgeben. </returns>
        <remarks>
            Es folgen die Namen der Parameter, die in der Konfigurationsdatei von Service Fabric Laden Sie die transporteinstellungen erkannt werden bereitgestellt werden soll.
                
                1. MaxQueueSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxQueueSize" />in langen Wert.
                2. MaxMessageSize - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxMessageSize" />Wert in Bytes.
                3. Drosselungen für MaxConcurrentCalls - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.MaxConcurrentCalls" />in langen Wert.
                4. SecurityCredentials - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.SecurityCredentials" /> Wert.
                5. OperationTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.OperationTimeout" /> Wert in Sekunden.
                6. KeepAliveTimeoutInSeconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.KeepAliveTimeout" /> Wert in Sekunden.
                7. ConnectTimeoutInMilliseconds - <see cref="P:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.FabricTransportRemotingSettings.ConnectTimeout" /> Wert in Millisekunden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>