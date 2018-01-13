<Type Name="Message+SystemPropertiesCollection" FullName="Microsoft.Azure.ServiceBus.Message+SystemPropertiesCollection">
  <TypeSignature Language="C#" Value="public sealed class Message.SystemPropertiesCollection" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit Message/SystemPropertiesCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Message.SystemPropertiesCollection" />
  <TypeSignature Language="F#" Value="type Message.SystemPropertiesCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Auflistung verwendet, um Eigenschaften zu speichern, die vom Service Bus-Dienst festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SystemPropertiesCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterSource">
      <MemberSignature Language="C#" Value="public string DeadLetterSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeadLetterSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeadLetterSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterSource As String" />
      <MemberSignature Language="F#" Value="member this.DeadLetterSource : string" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeadLetterSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Warteschlange oder einem Abonnement ab, diese Nachricht in die Warteschlange eingereiht, war, bevor es als unzustellbar gekennzeichnet war.
            </summary>
        <value>To be added.</value>
        <remarks>
                Only set in messages that have been dead-lettered and subsequently auto-forwarded from the dead-letter queue 
                zu einer anderen Entität. Gibt die Entität an, in der die Nachricht unzustellbar war. Diese Eigenschaft ist schreibgeschützt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen der aktuellen Übermittlungsanzahl an.
            </summary>
        <value>Dieser Wert beginnt mit 1.</value>
        <remarks>
               Anzahl der Zustellversuche dieser Nachricht. Die Anzahl wird erhöht, wenn eine Nachrichtensperre abläuft oder die Nachricht vom Empfänger explizit abgewiesen wird. Diese Eigenschaft ist schreibgeschützt.
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long EnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EnqueuedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die ursprüngliche Sequenznummer der Nachricht fest.</summary>
        <value>Die in die Warteschlange eingereihten Sequenznummer der Nachricht.</value>
        <remarks>
            Bei Nachrichten, die automatisch weitergeleitet wurden, entspricht diese Eigenschaft der Sequenznummer, die der Nachricht zum Zeitpunkt ihrer ursprünglichen Übermittlung zugewiesen wurde. Diese Eigenschaft ist schreibgeschützt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt Datum und Uhrzeit der gesendeten Zeit in UTC.</summary>
        <value>Die in die Warteschlange einzureihen Zeit in UTC. </value>
        <remarks>
               Der UTC-Moment, in dem die Nachricht angenommen und in der Entität gespeichert wurde. Dieser Wert kann als autoritative und neutrale Eingangszeitangabe verwendet werden, wenn der Empfänger der Uhr des Absenders nicht vertrauen möchte. Diese Eigenschaft ist schreibgeschützt.
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLockTokenSet">
      <MemberSignature Language="C#" Value="public bool IsLockTokenSet { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsLockTokenSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsLockTokenSet" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsLockTokenSet As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsLockTokenSet : bool" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsLockTokenSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob eine Sperrtoken, legen Sie für die aktuelle Nachricht vorhanden ist.
            </summary>
        <value>To be added.</value>
        <remarks>Ein Sperrtoken werden nur angegeben, wenn die Nachricht empfangen wurde<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReceived">
      <MemberSignature Language="C#" Value="public bool IsReceived { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsReceived" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReceived As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReceived : bool" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt an, ob die Nachricht aus der Broker abgerufen wurde.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Datum und die Uhrzeit in UTC bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</summary>
        <value>Das Datum und die Uhrzeit, die bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</value>
        <remarks>
                For messages retrieved under a lock (peek-lock receive mode, not pre-settled) this property reflects the UTC 
                Zeitpunkt, bis zu dem die Nachricht verbleibt, im der Warteschlange/Abonnement gesperrt ist. Nach Ablauf der Sperre der <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" /> wird erhöht, und die Nachricht wird erneut zum Abrufen verfügbar. Diese Eigenschaft ist schreibgeschützt.
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public string LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As String" />
      <MemberSignature Language="F#" Value="member this.LockToken : string" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Sperre für die aktuelle Nachricht ab.
            </summary>
        <value>To be added.</value>
        <remarks>
              Das Sperrtoken ist ein Verweis auf die Sperre, die vom Broker in gehalten wird <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> Modus. Sperren werden verwendet, um Nachrichten explizit ausgleichen, wie beschrieben in der <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-transfers-locks-settlement">Produktdokumentation ausführlicher</a>.
              Das Token kann auch verwendet werden, um die Sperre endgültig durch anheften der <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-deferral">Deferral API</a> und bei, die die Nachricht aus der regulären Delivery Status Datenfluss verwendet werden. Diese Eigenschaft ist schreibgeschützt.
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die eindeutige Nummer, die eine Nachricht vom Service Bus zugewiesen.</summary>
        <value>To be added.</value>
        <remarks>
                Die Sequenznummer ist eine eindeutige ganze 64-Bit-Zahl, die einer Nachricht zugeordnet wird, sobald sie vom Broker akzeptiert und gespeichert wird, und fungiert als ihr tatsächlicher Bezeichner. Bei partitionierte Entitäten stellen die obersten 16 Bits den Partitionsbezeichner dar. Sequenznummern erhöhen monoton. Sie werden auf 0 zurückgesetzt, sobald der 48-64-Bit-Bereich ausgeschöpft ist. Diese Eigenschaft ist schreibgeschützt.
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>