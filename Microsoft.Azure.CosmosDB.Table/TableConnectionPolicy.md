<Type Name="TableConnectionPolicy" FullName="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy">
  <TypeSignature Language="C#" Value="public sealed class TableConnectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableConnectionPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableConnectionPolicy" />
  <TypeSignature Language="F#" Value="type TableConnectionPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die zugeordnete Verbindungsrichtlinie <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> zur Verbindung mit des Azure-CosmosDB-tabellendiensts.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableConnectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /> Klasse, um die Verbindung mit dem Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableEndpointDiscovery">
      <MemberSignature Language="C#" Value="public bool EnableEndpointDiscovery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableEndpointDiscovery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableEndpointDiscovery As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableEndpointDiscovery : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Flag zum Endpunkt-Ermittlung für geografisch repliziert Datenbankkonten im Azure-Cosmos-DB-Dienst zu aktivieren.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Wert dieser Eigenschaft "true ist", das SDK automatisch die aktuellen schreiben erkennt und Lese Regionen, um sicherzustellen, dass Anforderungen an die richtige Region basierend auf den Regionen, die im angegebenen gesendet werden die <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" /> Eigenschaft.
            <value>Standardwert ist "true", der angibt, Endpunkt-Ermittlung aktiviert ist.</value></remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnectionLimit">
      <MemberSignature Language="C#" Value="public int MaxConnectionLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnectionLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxConnectionLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnectionLimit As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnectionLimit : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxConnectionLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl gleichzeitiger Verbindungen für den Ziel-Dienstendpunkt im Azure-Cosmos-DB-Dienst zulässig.
            </summary>
        <value>Standardwert ist 50.</value>
        <remarks>
            Diese Einstellung gilt nur in der Gateway-Modus.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryAttemptsOnThrottledRequests">
      <MemberSignature Language="C#" Value="public int MaxRetryAttemptsOnThrottledRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryAttemptsOnThrottledRequests As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryAttemptsOnThrottledRequests : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryAttemptsOnThrottledRequests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl der Wiederholungsversuche im Fall, in dem die Anforderung schlägt fehl, da der Dienst Azure-Cosmos-DB Begrenzung von aufrufraten, auf dem Client angewendet wurde.
            </summary>
        <value>
            Der Standardwert ist 9. Dies bedeutet, dass im Fall, in dem die Anforderung Rate begrenzt wird, ist, die gleiche Anforderung ausgegeben für maximal 10 Mal an den Server vor dem Fehler an die Anwendung zurückgegeben wird. Wenn der Wert dieser Eigenschaft auf 0 festgelegt ist, keine automatische Wiederholung auf Begrenzung von aufrufraten, die Clientanforderungen werden, und die Ausnahme muss auf Anwendungsebene behandelt. 
            </value>
        <remarks>
          <para>
            Wenn ein Client fordert schneller als die zulässige Rate sendet, wird vom Dienst HttpStatusCode 429 (zu viele Anforderung) auf den Grenzwert für den Client zurückgegeben. Die aktuelle Implementierung im SDK wartet dann für den Zeitraum, den der Dienst weist warten, und wiederholen Sie dann die Zeit verstrichen ist.  
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryWaitTimeInSeconds">
      <MemberSignature Language="C#" Value="public int MaxRetryWaitTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryWaitTimeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryWaitTimeInSeconds : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryWaitTimeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Wiederholungszeit in Sekunden für den Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der Standardwert ist 30 Sekunden. 
            </value>
        <remarks>
          <para>
            Bei einem aufgrund einer Begrenzung von aufrufraten, Fehler Anforderungsfehler, sendet der Dienst wieder eine Antwort, die dar, die einen Wert, der angibt, dass der Client nicht erneut sollte vor Ablauf des Zeitraums enthält. Diese Eigenschaft kann die Anwendung auf eine maximalen Wartezeit festgelegt, für alle Wiederholungsversuchen.
            Wenn die kumulierte Wartezeit diesen überschreitet Wert, der Client beendet, und wiederholen Sie dann und der Fehler an die Anwendung zurückgegeben.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreferredLocations">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; PreferredLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; PreferredLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreferredLocations As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.PreferredLocations : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt und definiert die bevorzugte Speicherorte (Regionen) für geografisch repliziert Datenbankkonten im Azure-Cosmos-DB-Dienst. Beispiel: "East US" als bevorzugten Speicherort.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Wenn <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" /> ist "true" und der Wert dieser Eigenschaft ist nicht leer, das SDK verwendet die Speicherorten in der Auflistung in der Reihenfolge angegebenen Operationen andernfalls ausführen, wenn der Wert dieser Eigenschaft nicht angegeben wird, das SDK verwendet den Write-Region wie die Bevorzugter Speicherort für alle Vorgänge.
            </para>
          <para>
            Wenn <see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" /> festgelegt ist auf "false", wird der Wert dieser Eigenschaft ignoriert. 
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDirectMode">
      <MemberSignature Language="C#" Value="public bool UseDirectMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDirectMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseDirectMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDirectMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDirectMode : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseDirectMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Direct-Modus verwenden beim Verbinden mit Azure-Cosmos-DB Service Flase verbindet sich über REST-API-Tabelle 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentSuffix">
      <MemberSignature Language="C#" Value="public string UserAgentSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UserAgentSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentSuffix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentSuffix : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UserAgentSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Suffix an Standardeinstellung User-Agent für den Azure-Cosmos-DB-Dienst hinzugefügt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Durch Festlegen dieser Eigenschaft nach dem Senden einer Anforderung keine Auswirkung.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTcpProtocol">
      <MemberSignature Language="C#" Value="public bool UseTcpProtocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseTcpProtocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseTcpProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTcpProtocol As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseTcpProtocol : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseTcpProtocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Verwenden Sie die TCP-Verbindung-Protokoll beim Verbinden mit der Azure-Cosmos-DB-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>
            Weitere Informationen finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#use-tcp">Verbindungsrichtlinie: Verwenden Sie das TCP-Protokoll</see>.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>