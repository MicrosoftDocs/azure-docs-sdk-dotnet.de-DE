<Type Name="SessionHandlerOptions" FullName="Microsoft.Azure.ServiceBus.SessionHandlerOptions">
  <TypeSignature Language="C#" Value="public sealed class SessionHandlerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionHandlerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionHandlerOptions" />
  <TypeSignature Language="F#" Value="type SessionHandlerOptions = class" />
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
    <summary>Bietet Optionen, die zugeordnete Sitzung Datapump Verarbeitung mit <see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> und <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionHandlerOptions (Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionHandlerOptions.#ctor(System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionHandlerOptions : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; Microsoft.Azure.ServiceBus.SessionHandlerOptions" Usage="new Microsoft.Azure.ServiceBus.SessionHandlerOptions exceptionReceivedHandler" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="exceptionReceivedHandler">Ein <see cref="T:System.Func`2" /> , die während der Ausnahmen aufgerufen wird.
            <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />die Kontextinformationen hinsichtlich der Ausnahme enthält.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.ServiceBus.SessionHandlerOptions" />-Klasse.
            Standardwerte: <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" /> = 2000 <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" /> = "true" <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" /> = 1 Minute <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" /> = 5 Minuten
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" />
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
        <summary>Ruft ab oder legt fest, ob die Option AutoVervollständigen-Funktion den Handler für die Sitzung aktiviert ist.</summary>
        <value>"true", wenn die Option AutoVervollständigen-Funktion den Handler für die Sitzung aktiviert ist; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceivedHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; ExceptionReceivedHandler { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; ExceptionReceivedHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.ExceptionReceivedHandler" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task)" />
      <MemberSignature Language="F#" Value="member this.ExceptionReceivedHandler : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt;" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.ExceptionReceivedHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Tritt auf, wenn eine Ausnahme empfangen wird. Können Sie alle aufgetretenen durch die Sitzung Datapump benachrichtigt zu werden.
            Beim Empfang von Fehlern werden Anrufe automatisch wiederholt werden also nur zu Informationszwecken. </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAutoRenewDuration">
      <MemberSignature Language="C#" Value="public TimeSpan MaxAutoRenewDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxAutoRenewDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAutoRenewDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxAutoRenewDuration : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Dauer, für die die Sperre für die Sitzung automatisch erneuert wird.</summary>
        <value>Die Dauer, für die der Sitzung zu erneuern Datenbankzustands.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentSessions">
      <MemberSignature Language="C#" Value="public int MaxConcurrentSessions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentSessions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentSessions As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentSessions : int with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" />
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
        <summary>Ruft ab oder legt die maximale Anzahl der vorhandenen Sitzungen, die der Benutzer möchte gleichzeitig zu verarbeiten.</summary>
        <value>Die maximale Anzahl von Sitzungen, die der Benutzer möchte gleichzeitig zu verarbeiten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageWaitTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MessageWaitTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MessageWaitTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageWaitTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MessageWaitTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Verzögerung bis zum Empfangen einer Nachricht.</summary>
        <value>Der Zeitpunkt, zum Empfangen der Nachricht gewartet werden soll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>