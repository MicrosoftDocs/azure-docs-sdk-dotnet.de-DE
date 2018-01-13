<Type Name="IMessageSession" FullName="Microsoft.Azure.ServiceBus.IMessageSession">
  <TypeSignature Language="C#" Value="public interface IMessageSession : Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSession implements class Microsoft.Azure.ServiceBus.Core.IMessageReceiver, class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.IMessageSession" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSession&#xA;Implements IMessageReceiver" />
  <TypeSignature Language="F#" Value="type IMessageSession = interface&#xA;    interface IMessageReceiver&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageReceiver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Beschreibt ein Sitzungsobjekt. IMessageSession kann zum Ausführen von Vorgängen für Sitzungen verwendet werden.
            </summary>
    <remarks>
      <para>
            Service Bus-Sitzungen, so genannte "Gruppen" in das Protokoll AMQP 1.0 sind ungebundenen Ereignisfolgen zusammengehöriger Nachrichten. Service Bus garantiert die Reihenfolge der Nachrichten in einer Sitzung.
            </para>
      <para>
            Alle Absender erstellen Sie eine Sitzung beim Senden von Nachrichten in einer Warteschlange oder ein Thema durch Festlegen der <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" /> Eigenschaft Nachricht zu einer Anwendung definierter Eindeutiger Bezeichner. Auf der Protokollebene AMQP 1.0 wird dieser Wert auf die Gruppen-Id-Eigenschaft zugeordnet.
            </para>
      <para>
            Sitzungen sind vorhanden, wenn mindestens eine Nachricht mit der Sitzung SessionId in die Warteschlange oder ein Thema Abonnement vorhanden ist.
            Sobald eine Sitzung vorhanden ist, gibt es keine definierten Moment oder einer Geste für, wenn die Sitzung abläuft, oder wird nicht mehr angezeigt.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; GetStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; GetStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStateAsync () As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member GetStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iMessageSession.GetStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft den Sitzungsstatus ab.
            </summary>
        <returns>Der Sitzungsstatus als Bytearray.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IMessageSession.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.IMessageSession.LockedUntilUtc" />
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
        <summary>
            Ruft die Zeit ab, die die identifizierte Sitzung <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> erst für diesen Client gesperrt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewSessionLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewSessionLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewSessionLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.RenewSessionLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewSessionLockAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member RenewSessionLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iMessageSession.RenewSessionLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erneuert die Sperre für die Sitzung, die gemäß der <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />. Die Sperre wird basierend auf der Einstellung für die Entität angegeben erneuert werden.
            </summary>
        <returns>Der asynchrone Vorgang</returns>
        <remarks>
          <para>
            Wenn Sie eine Sitzung annehmen, wird die Sitzung während der Erstellung der Warteschlange/Abonnement für diese Clientinstanz vom Dienst für eine Dauer entsprechend den Angaben gesperrt.
            Wenn länger als diese Dauer der Sitzung Verarbeitung erforderlich ist, muss die Sitzung-Sperre erneuert werden. Bei jeder Verlängerung er setzt die Uhrzeit zurück, für die Sitzung durch die LockDuration, legen Sie für die Entität gesperrt ist.
            </para>
          <para>
            Erneuerung der Sitzung werden alle Nachrichten in der Sitzung auch erneuert. Jede einzelne Nachricht muss nicht erneuert werden.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string" Usage="Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />
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
            Ruft die SessionId ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync (byte[] sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStateAsync(unsigned int8[] sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.SetStateAsync(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function SetStateAsync (sessionState As Byte()) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetStateAsync : byte[] -&gt; System.Threading.Tasks.Task" Usage="iMessageSession.SetStateAsync sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="sessionState">Ein Bytearray des Sitzungsstatus</param>
        <summary>
            Legen Sie einen benutzerdefinierten Zustand für die Sitzung mit einem späteren Zeitpunkt abgerufen werden kann<see cref="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" /></summary>
        <returns>To be added.</returns>
        <remarks>Dieser Status wird ewig auf Service Bus gespeichert, wenn Sie einen leeren Zustand festzulegen.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>