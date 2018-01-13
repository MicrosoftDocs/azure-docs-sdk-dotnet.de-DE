<Type Name="IMessageSessionHandlerFactory" FullName="Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory">
  <TypeSignature Language="C#" Value="public interface IMessageSessionHandlerFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSessionHandlerFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSessionHandlerFactory" />
  <TypeSignature Language="F#" Value="type IMessageSessionHandlerFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>Stellt eine Schnittstelle für die Handlerfactory, die die nachrichtensitzung zugeordnet ist.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.IMessageSessionHandler CreateInstance (Microsoft.ServiceBus.Messaging.MessageSession session, Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.IMessageSessionHandler CreateInstance(class Microsoft.ServiceBus.Messaging.MessageSession session, class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory.CreateInstance(Microsoft.ServiceBus.Messaging.MessageSession,Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance (session As MessageSession, message As BrokeredMessage) As IMessageSessionHandler" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : Microsoft.ServiceBus.Messaging.MessageSession * Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; Microsoft.ServiceBus.Messaging.IMessageSessionHandler" Usage="iMessageSessionHandlerFactory.CreateInstance (session, message)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.IMessageSessionHandler</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="session" Type="Microsoft.ServiceBus.Messaging.MessageSession" />
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="session">Die Message-Sitzung.</param>
        <param name="message">Die Meldung.</param>
        <summary>Erstellt eine Instanz der Handlerfactory.</summary>
        <returns>Die erstellte Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisposeInstance">
      <MemberSignature Language="C#" Value="public void DisposeInstance (Microsoft.ServiceBus.Messaging.IMessageSessionHandler handler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DisposeInstance(class Microsoft.ServiceBus.Messaging.IMessageSessionHandler handler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory.DisposeInstance(Microsoft.ServiceBus.Messaging.IMessageSessionHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisposeInstance (handler As IMessageSessionHandler)" />
      <MemberSignature Language="F#" Value="abstract member DisposeInstance : Microsoft.ServiceBus.Messaging.IMessageSessionHandler -&gt; unit" Usage="iMessageSessionHandlerFactory.DisposeInstance handler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="Microsoft.ServiceBus.Messaging.IMessageSessionHandler" />
      </Parameters>
      <Docs>
        <param name="handler">Die Ereignishandler-Instanz.</param>
        <summary>Gibt die Ereignishandler-Factory-Instanz zugeordneten Ressourcen frei.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>