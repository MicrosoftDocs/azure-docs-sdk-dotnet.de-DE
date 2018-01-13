<Type Name="TableRequestOptions" FullName="Microsoft.Azure.CosmosDB.Table.TableRequestOptions">
  <TypeSignature Language="C#" Value="public sealed class TableRequestOptions : Microsoft.Azure.Storage.IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableRequestOptions extends System.Object implements class Microsoft.Azure.Storage.IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableRequestOptions&#xA;Implements IRequestOptions" />
  <TypeSignature Language="F#" Value="type TableRequestOptions = class&#xA;    interface IRequestOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Storage.IRequestOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine Reihe von Optionen für Timeout- und wiederholungsrichtlinien, die für eine Anforderung für den Tabellendienst angegeben werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableRequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableRequestOptions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.#ctor(Microsoft.Azure.CosmosDB.Table.TableRequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As TableRequestOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableRequestOptions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions -&gt; Microsoft.Azure.CosmosDB.Table.TableRequestOptions" Usage="new Microsoft.Azure.CosmosDB.Table.TableRequestOptions other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
      </Parameters>
      <Docs>
        <param name="other">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> Objekt verwendet, um eine neue Instanz der Initialisieren der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> Klasse.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />-Klasse mit der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy EncryptionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy EncryptionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionPolicy As TableEncryptionPolicy" />
      <MemberSignature Language="F#" Value="member this.EncryptionPolicy : Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Verschlüsselungsrichtlinie für die Anforderung.
            </summary>
        <value>Ein Objekt vom Typ <see cref="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionResolver">
      <MemberSignature Language="C#" Value="public Func&lt;string,string,string,bool&gt; EncryptionResolver { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`4&lt;string, string, string, bool&gt; EncryptionResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionResolver" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionResolver As Func(Of String, String, String, Boolean)" />
      <MemberSignature Language="F#" Value="member this.EncryptionResolver : Func&lt;string, string, string, bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.String,System.String,System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Delegat, der den Wert, der angibt, und zwar unabhängig davon, ob eine Eigenschaft verschlüsselt werden sollen, erhält die Partitionsschlüssel, Zeilenschlüssel und Eigenschaftsnamen abrufen. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.LocationMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Positionsmodus der Anforderung fest.
            </summary>
        <value>Ein <see cref="T:Microsoft.Azure.Storage.RetryPolicies.LocationMode" /> -Enumerationswert, der angibt, des Positionsmodus der Anforderung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.MaximumExecutionTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Ausführungszeit für alle möglichen Wiederholungen für die Anforderung.
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> , die die maximale Ausführungszeit für Wiederholungen für die Anforderung darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PayloadFormat">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; PayloadFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; PayloadFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PayloadFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property PayloadFormat As Nullable(Of TablePayloadFormat)" />
      <MemberSignature Language="F#" Value="member this.PayloadFormat : Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PayloadFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePayloadFormat" /> , für die Anforderung verwendet wird.
            </summary>
        <value>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePayloadFormat" />-Enumerationswert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProjectSystemProperties">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ProjectSystemProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ProjectSystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ProjectSystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property ProjectSystemProperties As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ProjectSystemProperties : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ProjectSystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Option zum Einbeziehen von Systemeigenschaften wie z. B. Partitionsschlüssel und Zeilenschlüssel in Abfragen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyResolver">
      <MemberSignature Language="C#" Value="public Func&lt;string,string,string,string,Microsoft.Azure.CosmosDB.Table.EdmType&gt; PropertyResolver { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`5&lt;string, string, string, string, valuetype Microsoft.Azure.CosmosDB.Table.EdmType&gt; PropertyResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PropertyResolver" />
      <MemberSignature Language="VB.NET" Value="Public Property PropertyResolver As Func(Of String, String, String, String, EdmType)" />
      <MemberSignature Language="F#" Value="member this.PropertyResolver : Func&lt;string, string, string, string, Microsoft.Azure.CosmosDB.Table.EdmType&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PropertyResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.String,System.String,System.String,Microsoft.Azure.CosmosDB.Table.EdmType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Delegaten ab, das Abrufen der <see cref="T:Microsoft.Azure.CosmosDB.Table.EdmType" /> für eine Entitätseigenschaft, die den Partitionsschlüssel, Zeilenschlüssel und den Namen der Eigenschaft zugewiesen. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.RequireEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert anzugeben, ob die Daten geschrieben und gelesen werden, von der Clientbibliothek verschlüsselt werden sollen.
            </summary>
        <value>Verwendung <c>"true"</c> um anzugeben, dass die Daten werden soll, für alle Transaktionen verschlüsselt und entschlüsselt, und andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.RetryPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die wiederholungsrichtlinie für die Anforderung.
            </summary>
        <value>Ein Objekt vom Typ <see cref="T:Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.ServerTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest das Timeoutintervall für die Anforderung.
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> mit dem servertimeoutintervall für die Anforderung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.SessionToken" />
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
            Ruft ab oder legt das Token für die Verwendung mit sitzungskonsistenz im Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Das Token für die Verwendung mit sitzungskonsistenz.
            </value>
        <remarks>
            Eines der <see cref="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" /> für Azure-Cosmos-DB Sitzung ist.  
            <para>Bei der Arbeit mit sitzungskonsistenz wird jede neue schreibanforderung an Azure Cosmos-Datenbank eine neue SessionToken zugewiesen.
            Die <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> verwendet dieses Token intern mit jeder Anforderung Lese-/Abfragen, stellen Sie sicher, dass die Set-konsistenzebene beibehalten wird.
            
             <para>In einigen Szenarien müssen Sie diese Sitzung selbst verwalten. Betrachten Sie eine Webanwendung mit mehreren Knoten, wird jeder Knoten eine eigene Instanz des <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> mussten Sie diese Knoten zur Teilnahme an der gleichen Sitzungs (in der Lage sein gelesen eigene Schreibvorgänge konsistent über Webebenen) müssen Sie die SessionToken senden aus einem der Schreibvorgang auf einen Knoten, die die Clientebene, ein Cookie oder eines anderen Mechanismus, verwenden und diese tokenfluss zurück an die Webebene für nachfolgende Lesevorgänge.
            Wenn Sie einen Roundrobin-Lastenausgleich der sitzungsaffinität zwischen Anforderungen, z. B. Azure-Lastenausgleichs nicht verwaltet mithilfe,  
            die schreibgeschützte konnte potenziell transformationsschritten in einem anderen Knoten auf die schreibanforderung, in dem die Sitzung erstellt wurde. 
            </para><para>Wenn Sie die Azure Cosmos DB SessionToken über erst übernommen, wie oben beschrieben, konnte Sie inkonsistente gelesenen Ergebnisse für eine bestimmte Zeitspanne zum Schluss.</para></para></remarks>
        <altmember cref="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" />
      </Docs>
    </Member>
  </Members>
</Type>