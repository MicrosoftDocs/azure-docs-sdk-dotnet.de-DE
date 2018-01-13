<Type Name="FabricClient" FullName="System.Fabric.FabricClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type FabricClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public members from V1.")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1204:StaticElementsMustAppearBeforeInstanceElements", Justification="Current grouping improves readability.")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1202:ElementsMustBeOrderedByAccess", Justification="Current grouping improves readability.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Erstellt und verwaltet Service Fabric-Dienste oder andere Einrichtungen weitergeben.</para>
    </summary>
    <remarks>
      <para>Es wird dringend empfohlen, dass Sie so weit wie möglich FabricClients freigeben.
                Dies ist, da die FabricClient mehrere Optimierungen verwendet, wie z. B. caching und Batchverarbeitung, dass Sie nicht vollständig nutzen Sie andernfalls wäre.
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricClient" />-Klasse. Dieser Konstruktor sollte von Code verwendet werden, die innerhalb des Clusters ausgeführt wird. Sie können die <see cref="T:System.Fabric.FabricClient" /> Instanz für die Verbindung mit dem Cluster über den lokalen Gateway-Dienst auf demselben Knoten ausgeführt wird.</para>
        </summary>
        <remarks>
          <para>Da dieser Konstruktor den lokalen Gateway-Dienst auf demselben Knoten ausgeführt für th-Cluster die Verbindung verwendet wird, kann der Client einen zusätzlicher Netzwerkhop umgangen werden. Zur Verbindung mit eines Clusters aus Code außerhalb eines Clusters ausgeführt wird, verwenden Sie einen anderen Konstruktor explizit die Verbindungsparameter angeben können.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientRole clientRole);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricClientRole clientRole) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientRole)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientRole As FabricClientRole)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientRole -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient clientRole" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRole" Type="System.Fabric.FabricClientRole" />
      </Parameters>
      <Docs>
        <param name="clientRole">
          <para>Die Fabric-Client-Rolle.</para>
        </param>
        <summary>
          <para>
            Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit den angegebenen Client fabricrolle - <see cref="T:System.Fabric.FabricClientRole" />.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientSettings -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient settings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>Die Fabric-Clienteinstellungen, die von den Fabric-Client verwendet wird.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit den gewünschten <see cref="T:System.Fabric.FabricClientSettings" />. Wenn die <see cref="T:System.Fabric.FabricClient" /> auf demselben Cluster wie der Dienst ist, dann verwenden Sie eine lokale <see cref="T:System.Fabric.FabricClient" />. Lokale <see cref="T:System.Fabric.FabricClient" /> ist ein Feature von Service Fabric, das ermöglicht die <see cref="T:System.Fabric.FabricClient" /> für die Verbindung mit dem lokalen Gateway-Dienst anstelle von aus einer Liste auswählen. Auf diese Weise kann der Client einen zusätzlicher Netzwerkhop umgangen werden. Im Fall Auflösen eines Diensts einen anderen Dienstpartition im selben Cluster, und es wird empfohlen, die Verwendung von lokalen <see cref="T:System.Fabric.FabricClient" />, wie es, den automatischen Lastenausgleich ermöglicht und die Leistung verbessert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient hostEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="hostEndpoints">
          <para>Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen Service Fabric-Gateway-Adressen. Diese Host-Endpunkte sind die Liste der ":" als Trennzeichen für Zeichenfolgen, wobei der erste Teil ist die IP-Adresse des Clusters und der zweite Teil ist die Clientverbindungs-Endpunkt-Port. </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientSettings settings, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientSettings * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (settings, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="settings">
          <para>Die Fabric-Clienteinstellungen.</para>
        </param>
        <param name="hostEndpoints">
          <para>Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen Service Fabric-Standardgatewayadressen und die gewünschte <see cref="T:System.Fabric.FabricClientSettings" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">
          <para>
            <see cref="T:System.Fabric.SecurityCredentials" />definiert die Sicherheitseinstellungen für die<see cref="T:System.Fabric.FabricClient" />.</para>
        </param>
        <param name="hostEndpoints">
          <para>Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> Klasse, mit Service Fabric-Standardgatewayadressen und <see cref="T:System.Fabric.SecurityCredentials" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (TimeSpan keepAliveInterval, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan keepAliveInterval, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.TimeSpan,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keepAliveInterval As TimeSpan, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : TimeSpan * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (keepAliveInterval, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated", true)</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="keepAliveInterval" Type="System.TimeSpan" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="keepAliveInterval">
          <para>Definiert das Intervall der periodischen Keep alive-Nachrichten.</para>
        </param>
        <param name="hostEndpoints">
          <para> Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</para>
        </param>
        <summary>
          <para>ALS VERALTET MARKIERT. Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen KeepAliveInterval und Service Fabric-Standardgatewayadressen (HostEndpoints).</para>
        </summary>
        <remarks>
          <para>Wenn externe Geräte zwischen die Verbindung vom Client zum Cluster, die regelmäßige Nachrichten an die Verbindung aufrechtzuerhalten erfordern vorhanden sind, stellen Sie sicher, dass die Funktion "Keepalive" FabricClient verwenden. Während der Initialisierung der FabricClient können Benutzer einen TimeSpan-KeepAliveInterval angeben. Wenn dieses Argument angegeben wird, führt dann die FabricClient in regelmäßigen Abständen ping derzeit kommuniziert mit diesem Service Fabric-Gatewaydienst als ein ausstehender Vorgang vorhanden ist. Ein Beispiel für ein Szenario, in dem diese Funktion hilfreich ist, ist Windows Azure. Wenn die <see cref="T:System.Fabric.FabricClient" /> außerhalb von Windows Azure wird der Cluster ist in Windows Azure, und alle Verbindungen über Azure Load Balancer (ALB) wechseln. ALB beendet-Verbindungen, die mehr als 60 Sekunden lang im Leerlauf befinden. Daher wird in diesen Situationen <see cref="T:System.Fabric.FabricClient" /> erstellt werden soll, mit KeepAliveInterval festgelegt &lt;59 Sekunden (20 -30 wird empfohlen).</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, System.Fabric.FabricClientSettings settings, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, class System.Fabric.FabricClientSettings settings, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, settings As FabricClientSettings, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * System.Fabric.FabricClientSettings * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, settings, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">
          <para>
            <see cref="T:System.Fabric.SecurityCredentials" />definiert die Sicherheitseinstellungen für die<see cref="T:System.Fabric.FabricClient" />.</para>
        </param>
        <param name="settings">
          <para>Die Fabric-Clienteinstellungen.</para>
        </param>
        <param name="hostEndpoints">
          <para>Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen Service Fabric-Gateway-Adressen <see cref="T:System.Fabric.SecurityCredentials" /> und <see cref="T:System.Fabric.FabricClientSettings" />.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, TimeSpan keepAliveInterval, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, valuetype System.TimeSpan keepAliveInterval, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.TimeSpan,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, keepAliveInterval As TimeSpan, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * TimeSpan * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, keepAliveInterval, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated", true)</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="keepAliveInterval" Type="System.TimeSpan" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">Definieren der Sicherheitsanmeldeinformationen.</param>
        <param name="keepAliveInterval">
          <para>Definiert das Intervall der periodischen Keep alive-Nachrichten.</para>
        </param>
        <param name="hostEndpoints">
          <para> Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</para>
        </param>
        <summary>
          <para>ALS VERALTET MARKIERT. Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen Anmeldeinformationen, KeepAliveInterval und Service Fabric-Standardgatewayadressen (HostEndpoints).</para>
        </summary>
        <remarks>
          <para>Wenn externe Geräte zwischen die Verbindung vom Client zum Cluster, die regelmäßige Nachrichten an die Verbindung aufrechtzuerhalten erfordern vorhanden sind, stellen Sie sicher, dass die Funktion "Keepalive" FabricClient verwenden. Während der Initialisierung der FabricClient können Benutzer einen TimeSpan-KeepAliveInterval angeben. Wenn dieses Argument angegeben wird, führt dann die FabricClient in regelmäßigen Abständen ping derzeit kommuniziert mit diesem Service Fabric-Gatewaydienst als ein ausstehender Vorgang vorhanden ist. Ein Beispiel für ein Szenario, in dem diese Funktion hilfreich ist, ist Windows Azure. Wenn die <see cref="T:System.Fabric.FabricClient" /> außerhalb von Windows Azure wird der Cluster ist in Windows Azure, und alle Verbindungen über Azure Load Balancer (ALB) wechseln. ALB beendet-Verbindungen, die mehr als 60 Sekunden lang im Leerlauf befinden. Daher wird in diesen Situationen <see cref="T:System.Fabric.FabricClient" /> erstellt werden soll, mit KeepAliveInterval festgelegt &lt;59 Sekunden (20 -30 wird empfohlen).</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ApplicationManagementClient ApplicationManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ApplicationManagementClient ApplicationManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ApplicationManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationManager As FabricClient.ApplicationManagementClient" />
      <MemberSignature Language="F#" Value="member this.ApplicationManager : System.Fabric.FabricClient.ApplicationManagementClient" Usage="System.Fabric.FabricClient.ApplicationManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ApplicationManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="P:System.Fabric.FabricClient.ApplicationManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Anwendungen und Anwendungstypen verwendet werden kann.</para>
        </summary>
        <value>
          <para>Die <see cref="P:System.Fabric.FabricClient.ApplicationManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Anwendungen und Anwendungstypen verwendet werden kann.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClaimsRetrieval">
      <MemberSignature Language="C#" Value="public event System.Fabric.FabricClient.ClaimsRetrievalEventHandler ClaimsRetrieval;" />
      <MemberSignature Language="ILAsm" Value=".event class System.Fabric.FabricClient/ClaimsRetrievalEventHandler ClaimsRetrieval" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClaimsRetrieval" />
      <MemberSignature Language="VB.NET" Value="Public Event ClaimsRetrieval As FabricClient.ClaimsRetrievalEventHandler " />
      <MemberSignature Language="F#" Value="member this.ClaimsRetrieval : System.Fabric.FabricClient.ClaimsRetrievalEventHandler " Usage="member this.ClaimsRetrieval : System.Fabric.FabricClient.ClaimsRetrievalEventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ClaimsRetrievalEventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn der Client einem Claims-Token für die Autorisierung mit dem Gateway bereitstellen muss
            </summary>
        <remarks>
          <para>
            Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster#connect-to-a-secure-cluster-using-the-fabricclient-apis" /> zum Herstellen einer Verbindung zum sicheren Cluster mithilfe der Azure Active Directory-Authentifizierung.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ClientConnected" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler " Usage="member this.ClientConnected : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn der Client zum Gateway verbunden ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler " Usage="member this.ClientDisconnected : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Tritt auf, wenn der Client über das Gateway getrennt ist.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ClusterManagementClient ClusterManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ClusterManagementClient ClusterManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ClusterManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterManager As FabricClient.ClusterManagementClient" />
      <MemberSignature Language="F#" Value="member this.ClusterManager : System.Fabric.FabricClient.ClusterManagementClient" Usage="System.Fabric.FabricClient.ClusterManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ClusterManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="P:System.Fabric.FabricClient.ClusterManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit der Service Fabric-Cluster verwendet werden kann.</para>
        </summary>
        <value>
          <para>Die <see cref="P:System.Fabric.FabricClient.ClusterManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit der Service Fabric-Cluster verwendet werden kann.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeDeploymentManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ComposeDeploymentClient ComposeDeploymentManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ComposeDeploymentClient ComposeDeploymentManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ComposeDeploymentManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComposeDeploymentManager As FabricClient.ComposeDeploymentClient" />
      <MemberSignature Language="F#" Value="member this.ComposeDeploymentManager : System.Fabric.FabricClient.ComposeDeploymentClient" Usage="System.Fabric.FabricClient.ComposeDeploymentManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ComposeDeploymentClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.FabricClient.ComposeDeploymentClient" /> , die zum Ausführen von Vorgängen im Zusammenhang mit der Bereitstellung verwendet werden kann.</para>
        </summary>
        <value>
          <para>Die <see cref="P:System.Fabric.FabricClient.ComposeDeploymentManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit der Bereitstellung verwendet werden kann.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="fabricClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Verwirft den Fabric-Client.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FabricSystemApplication">
      <MemberSignature Language="C#" Value="public readonly Uri FabricSystemApplication;" />
      <MemberSignature Language="ILAsm" Value=".field public initonly class System.Uri FabricSystemApplication" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FabricClient.FabricSystemApplication" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly FabricSystemApplication As Uri " />
      <MemberSignature Language="F#" Value="val mutable FabricSystemApplication : Uri" Usage="System.Fabric.FabricClient.FabricSystemApplication" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Die Service Fabric-System-Anwendung.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FaultManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.FaultManagementClient FaultManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/FaultManagementClient FaultManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.FaultManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FaultManager As FabricClient.FaultManagementClient" />
      <MemberSignature Language="F#" Value="member this.FaultManager : System.Fabric.FabricClient.FaultManagementClient" Usage="System.Fabric.FabricClient.FaultManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+FaultManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:System.Fabric.FabricClient.FaultManagementClient" /> zum Auslösen von Fehlern. Beispielsweise RestartNodeAsync.
            </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.FabricClient.FaultManagementClient" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~FabricClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="fabricClient.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Der Destruktor der Fabric-Client.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.HealthClient HealthManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/HealthClient HealthManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.HealthManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthManager As FabricClient.HealthClient" />
      <MemberSignature Language="F#" Value="member this.HealthManager : System.Fabric.FabricClient.HealthClient" Usage="System.Fabric.FabricClient.HealthManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+HealthClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Integritäts-Client, der verwendet werden kann, zum Ausführen von Integrität, die im Zusammenhang Vorgänge, wie z. B. Melden der Integrität oder Entitätsintegrität abrufen.</para>
        </summary>
        <value>
          <para>Die Integrität-Client, der verwendet werden kann, um integritätsprüfungen auszuführen im Zusammenhang mit Vorgängen, z. B. Melden der Integrität oder Get Entitätsintegrität.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InfrastructureManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.InfrastructureServiceClient InfrastructureManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/InfrastructureServiceClient InfrastructureManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.InfrastructureManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InfrastructureManager As FabricClient.InfrastructureServiceClient" />
      <MemberSignature Language="F#" Value="member this.InfrastructureManager : System.Fabric.FabricClient.InfrastructureServiceClient" Usage="System.Fabric.FabricClient.InfrastructureManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+InfrastructureServiceClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" /> , die verwendet werden kann, zum Ausführen von Vorgängen im Zusammenhang mit der Infrastruktur, die auf dem Cluster ausgeführt wird.</para>
          <para>Diese Eigenschaft unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" /> , die verwendet werden kann, zum Ausführen von Vorgängen im Zusammenhang mit der Infrastruktur, die auf dem Cluster ausgeführt wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.PropertyManagementClient PropertyManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/PropertyManagementClient PropertyManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.PropertyManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyManager As FabricClient.PropertyManagementClient" />
      <MemberSignature Language="F#" Value="member this.PropertyManager : System.Fabric.FabricClient.PropertyManagementClient" Usage="System.Fabric.FabricClient.PropertyManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+PropertyManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="P:System.Fabric.FabricClient.PropertyManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Namen und Eigenschaften verwendet werden kann.</para>
        </summary>
        <value>
          <para>Die <see cref="P:System.Fabric.FabricClient.PropertyManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Namen und Eigenschaften verwendet werden kann.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.QueryClient QueryManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/QueryClient QueryManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.QueryManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryManager As FabricClient.QueryClient" />
      <MemberSignature Language="F#" Value="member this.QueryManager : System.Fabric.FabricClient.QueryClient" Usage="System.Fabric.FabricClient.QueryManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+QueryClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Abfrage-Manager, der zum Ausführen von Abfragen für die Service Fabric-Cluster verwendet werden kann.</para>
        </summary>
        <value>
          <para>Der Abfrage-Manager, der zum Ausführen von Abfragen für die Service Fabric-Cluster verwendet werden kann.</para>
        </value>
        <remarks>
          <para>Der Abfrage-Manager kann zum Ausführen von Abfragen für den Cluster verwendet werden.
            Die meisten Abfragen verteilt werden. Sie rufen Sie mehrere Systemkomponenten, um verschiedene Informationen zu erhalten.
            Die Aufrufe an die Systemkomponenten werden parallel ausgeführt, und die zurückgegebenen Ergebnisse werden basierend auf einem gemeinsamen Schlüssel aggregiert.
            Beispielsweise, um die Liste der Knoten im Cluster ist, erhalten die <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> Abfrage wechselt zum Failovercluster-Manager, Cluster-Manager und Health Manager Systemdienste.
            Aus diesem Grund sind einige Abfragen teuer.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RepairManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.RepairManagementClient RepairManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/RepairManagementClient RepairManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.RepairManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepairManager As FabricClient.RepairManagementClient" />
      <MemberSignature Language="F#" Value="member this.RepairManager : System.Fabric.FabricClient.RepairManagementClient" Usage="System.Fabric.FabricClient.RepairManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+RepairManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="T:System.Fabric.FabricClient.RepairManagementClient" /> , die zur Verwaltung reparieren Aufgaben verwendet werden kann.</para>
          <para>Diese Eigenschaft unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.FabricClient.RepairManagementClient" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceGroupManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ServiceGroupManagementClient ServiceGroupManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ServiceGroupManagementClient ServiceGroupManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ServiceGroupManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceGroupManager As FabricClient.ServiceGroupManagementClient" />
      <MemberSignature Language="F#" Value="member this.ServiceGroupManager : System.Fabric.FabricClient.ServiceGroupManagementClient" Usage="System.Fabric.FabricClient.ServiceGroupManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ServiceGroupManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="P:System.Fabric.FabricClient.ServiceGroupManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Dienstgruppen verwendet werden kann.</para>
        </summary>
        <value>
          <para>Die <see cref="P:System.Fabric.FabricClient.ServiceGroupManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Dienstgruppen verwendet werden kann.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ServiceManagementClient ServiceManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ServiceManagementClient ServiceManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ServiceManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManager As FabricClient.ServiceManagementClient" />
      <MemberSignature Language="F#" Value="member this.ServiceManager : System.Fabric.FabricClient.ServiceManagementClient" Usage="System.Fabric.FabricClient.ServiceManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ServiceManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die <see cref="P:System.Fabric.FabricClient.ServiceManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Diensten und Diensttypen verwendet werden kann.</para>
        </summary>
        <value>
          <para>Die <see cref="P:System.Fabric.FabricClient.ServiceManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Diensten und Diensttypen verwendet werden kann.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClientSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClientSettings Settings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As FabricClientSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Fabric.FabricClientSettings" Usage="System.Fabric.FabricClient.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClientSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Fabric-Clienteinstellungen.</para>
        </summary>
        <value>
          <para>Die Fabric-Clienteinstellungen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.TestManagementClient TestManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/TestManagementClient TestManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.TestManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TestManager As FabricClient.TestManagementClient" />
      <MemberSignature Language="F#" Value="member this.TestManager : System.Fabric.FabricClient.TestManagementClient" Usage="System.Fabric.FabricClient.TestManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+TestManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:System.Fabric.FabricClient.TestManagementClient" /> für komplexe Aktionen, die FaultAnalysisService durchlaufen. Beispielsweise StartPartitionDataLossAsync.
            Dies unterstützt auch die APIs für die Überprüfung (die nicht über FaultAnalysisService geleitet werden). Beispielsweise ValidateServiceAsync.
            </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.FabricClient.TestManagementClient" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecurityCredentials">
      <MemberSignature Language="C#" Value="public void UpdateSecurityCredentials (System.Fabric.SecurityCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSecurityCredentials(class System.Fabric.SecurityCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.UpdateSecurityCredentials(System.Fabric.SecurityCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSecurityCredentials (credentials As SecurityCredentials)" />
      <MemberSignature Language="F#" Value="member this.UpdateSecurityCredentials : System.Fabric.SecurityCredentials -&gt; unit" Usage="fabricClient.UpdateSecurityCredentials credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="System.Fabric.SecurityCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Die neuen Anmeldeinformationen verwendet werden.</param>
        <summary>
            Aktualisiert die Fabric-Client-Sicherheitsanmeldeinformationen an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSettings">
      <MemberSignature Language="C#" Value="public void UpdateSettings (System.Fabric.FabricClientSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSettings(class System.Fabric.FabricClientSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.UpdateSettings(System.Fabric.FabricClientSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSettings (settings As FabricClientSettings)" />
      <MemberSignature Language="F#" Value="member this.UpdateSettings : System.Fabric.FabricClientSettings -&gt; unit" Usage="fabricClient.UpdateSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>Die neuen Fabric-Clienteinstellungen verwendet werden.</para>
        </param>
        <summary>
          <para>Aktualisiert die Fabric-Clienteinstellungen.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>Die angegebene Fabric-Clienteinstellungen darf nicht null sein.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
            <see cref="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" />muss größer oder gleich 0 (null) sein.</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>