<Type Name="SessionHandlerOptions" FullName="Microsoft.ServiceBus.Messaging.SessionHandlerOptions">
  <TypeSignature Language="C#" Value="public class SessionHandlerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SessionHandlerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class SessionHandlerOptions" />
  <TypeSignature Language="F#" Value="type SessionHandlerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt die Optionen für die Sitzung Handler dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionHandlerOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SessionHandlerOptions.AutoComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
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
    <Member MemberName="AutoRenewTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan AutoRenewTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoRenewTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.AutoRenewTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenewTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoRenewTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SessionHandlerOptions.AutoRenewTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Zeit, bis Sie die Sitzung zu erneuern Datenbankzustands.</summary>
        <value>Die Zeit benötigt den Zustand vor der Sitzung erneuern.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.ExceptionReceived" />
      <MemberSignature Language="VB.NET" Value="Public Event ExceptionReceived As EventHandler(Of ExceptionReceivedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ExceptionReceived : EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; " Usage="member this.ExceptionReceived : System.EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Tritt auf, wenn eine Ausnahme während der sitzungsverarbeitungsfunktionen empfangen wurde.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentSessions">
      <MemberSignature Language="C#" Value="public int MaxConcurrentSessions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentSessions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentSessions As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentSessions : int with get, set" Usage="Microsoft.ServiceBus.Messaging.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die maximale Anzahl der vorhandenen Sitzungen.</summary>
        <value>Die maximale Anzahl der vorhandenen Sitzungen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageWaitTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MessageWaitTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MessageWaitTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageWaitTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MessageWaitTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Zeit, die bereits vor Ablauf der Nachricht wartet.</summary>
        <value>Die Zeit vor Ablauf der Nachricht wartet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>