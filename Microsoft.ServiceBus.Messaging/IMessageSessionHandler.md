<Type Name="IMessageSessionHandler" FullName="Microsoft.ServiceBus.Messaging.IMessageSessionHandler">
  <TypeSignature Language="C#" Value="public interface IMessageSessionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSessionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IMessageSessionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSessionHandler" />
  <TypeSignature Language="F#" Value="type IMessageSessionHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>Stellt eine Schnittstelle für den Handler der meldungssitzung zugeordnet.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OnCloseSession">
      <MemberSignature Language="C#" Value="public void OnCloseSession (Microsoft.ServiceBus.Messaging.MessageSession session);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void OnCloseSession(class Microsoft.ServiceBus.Messaging.MessageSession session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnCloseSession(Microsoft.ServiceBus.Messaging.MessageSession)" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnCloseSession (session As MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseSession : Microsoft.ServiceBus.Messaging.MessageSession -&gt; unit" Usage="iMessageSessionHandler.OnCloseSession session" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
      </Parameters>
      <Docs>
        <param name="session">Das Schließen der Sitzung.</param>
        <summary>Löst ein Ereignis, das auftritt, wenn eine aktive Sitzung geschlossen wird.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void OnMessage(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnMessage(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (session As MessageSession, message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member OnMessage : Microsoft.ServiceBus.Messaging.MessageSession * Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="iMessageSessionHandler.OnMessage (session, message)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="session">Die aktuelle Nachricht-Sitzung.</param>
        <param name="message">Die vermittelte Nachricht.</param>
        <summary>Löst ein Ereignis, das auftritt, wenn eine Nachricht brokermessaging wurde.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSessionLost">
      <MemberSignature Language="C#" Value="public void OnSessionLost (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void OnSessionLost(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IMessageSessionHandler.OnSessionLost(System.Exception)" />
      <MemberSignature Language="F#" Value="abstract member OnSessionLost : Exception -&gt; unit" Usage="iMessageSessionHandler.OnSessionLost exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception">Der Fehler, der die Sitzung verlorene verursacht hat.</param>
        <summary>Löst ein Ereignis, das auftritt, wenn die Sitzung unterbrochen wurde.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>